# CSS Flexbox by Building a Photo Gallery

## 11

Flexbox is a one-dimensional CSS layout approach that focuses on the flow of content. It offers the ability to control the way items are spaced and aligned within a container.

To set an element to use Flexbox, you give it a display property set to flex. Create a #gallery selector and give it that property.

## 12

Flexbox can be thought of as having two axes, the main axis and the cross axis. The main axis is determined by the flex-direction property. If flex-direction is set to row or row-reverse, the main axis is horizontal. If flex-direction is set to column or column-reverse, the main axis is vertical.

Give your #gallery selector a flex-direction property set to row.

## 13

You may have noticed that your images have all moved onto the same row.

The flex-wrap property determines how your items should behave when the flex container is too small. Setting this property to wrap will allow your items to wrap to the next row/column (depending on your main axis), where nowrap will prevent your items from wrapping. When this is set to nowrap, items may either shrink to fit or overflow.

Give the #gallery selector a flex-wrap property set to wrap. You should see your images take a four-column layout. This is because you set their width to 25% in an earlier step.

## 14 

The justify-content property determines how the items inside a flex container are positioned along the main axis, affecting their position and the space around them.

Give your #gallery selector a justify-content property set to center.

## 15 

The align-items property positions the flex content along the cross axis. In this case, with your flex-direction set to row, your cross axis would be vertical.

To vertically center your images, give your #gallery selector an align-items property set to center.

Notice how some of your images have become distorted. This is because the images have different aspect ratios. Rather than setting each aspect ratio individually, you can use the object-fit property to determine how images should behave.
