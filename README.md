# Android_SBeauty_Set
记录一些安卓自带的小而美的功能类（包含一些不常用的View或其他工具）

### Transition

1.  主要用来做三件事：
    
-   Activity间的转场动画；
    
-   不同Activity或Fragment间元素共享，让交互更连贯；
    
-   同一个Activity之间一些View的变换动画。

### RecyclerView

- 给item添加水波纹：android:foreground="?android:attr/selectableItemBackground"
- SnapHelper：用于辅助RecyclerView在滚动结束时将Item对齐到某个位置。特别是列表横向滑动时，很多时候不会让列表滑到任意位置，而是会有一定的规则限制，这时候就可以通过SnapHelper来定义对齐规则了。
