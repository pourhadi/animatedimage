# AnimatedImage

A SwiftUI View for displaying and playing animated GIFs. Uses iOS 13's new CGAnimation API and Combine to feed images as a SwiftUI Image, eliminating the need for any UIKit views.

To use, pass a GIF file's Data or URL to a new AnimatedImage view, or create a type that conforms to ImageSequence and pass that instead.
