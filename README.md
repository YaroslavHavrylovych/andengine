![AndEgnine_image](https://koenig-media.raywenderlich.com/uploads/2012/05/AndEngine.png)

### AndEngine tribute

[AndEngine](https://github.com/nicolasgramlich/AndEngine/tree/GLES2-AnchorCenter)(anchor-center) 
repository fork, as the main repository is out of support.
Checkout [original readme](https://github.com/nicolasgramlich/AndEngine/blob/GLES2/README.md)
file to get more information.

### Why this repo

The original repo has a few issues which are not fixed. The only way I found was to branch-out.

### Useful links

The official AndEngine [page](http://www.andengine.org/)

The AndEngine community [page](http://andengine-community.com/)

The original 
[repo](https://github.com/nicolasgramlich/AndEngine/).

### Changes

* Gradle support
* `Velocity camera` added
* `SpriteBatch` entity positioning
* `ParallaxBackground` changes: in ParallaxEntity#onDraw(GLState, Camera,float) to work normally with ZoomCamera
* `reset(float pDuration, float pFromX, float pFromY, float pToX, float pToY)` added to MoveModifier
