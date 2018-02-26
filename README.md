# UIImageView+AnimationCompletionBlock

An `UIImageView` extension for UIImageView's animationImages completion callback.

## Example

    var imageArray: [UIImage] = []
    for i in 1...19 {
        imageArray.append(UIImage(named: "animateButton_\(i)") ?? UIImage())
    }
    self.innerCircle.animationImages = imageArray
    self.innerCircle.animationDuration = 3
    self.innerCircle.startAnimatingWithCompletionBlock {
        // do your completion stuff
    }
    
## LICENSE

MIT
