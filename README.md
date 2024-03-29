# Android View Animations

# Demo

![Google Drive](video/androidAssignment.gif)

# Usage

## Step 1

#### Gradle
```groovy
dependencies {
    compile 'com.android.support:support-compat:25.1.1'
    compile 'com.daimajia.easing:library:2.0@aar'
    compile 'com.daimajia.androidanimations:library:2.3@aar'
}
```
#### Maven

```xml
<dependency>
    <groupId>com.android.support</groupId>
    <artifactId>support-compat</artifactId>
    <version>25.1.1</version>
</dependency>
<dependency>
    <groupId>com.daimajia.androidanimation</groupId>
    <artifactId>library</artifactId>
    <version>2.3</version>
</dependency>
<dependency>
    <groupId>com.daimajia.easing</groupId>
    <artifactId>library</artifactId>
    <version>2.0</version>
</dependency>
```

## Step 2

```java
YoYo.with(Techniques.Tada)
    .duration(700)
    .repeat(5)
    .playOn(findViewById(R.id.edit_area));
```

### Effects
#### Attension
`Flash` `Pulse` `RubberBand` `Shake` `Swing` `Wobble` `Bounce` `Tada` `StandUp` `Wave`

#### Special
`Hinge` `RollIn` `RollOut` `Landing` `TakingOff` `DropOut`

#### Bounce
`BounceIn` `BounceInDown` `BounceInLeft` `BounceInRight` `BounceInUp`

#### Fade
`FadeIn` `FadeInUp` `FadeInDown` `FadeInLeft` `FadeInRight`

`FadeOut` `FadeOutDown` `FadeOutLeft` `FadeOutRight` `FadeOutUp`

#### Flip
`FlipInX` `FlipOutX` `FlipOutY`

#### Rotate
`RotateIn` `RotateInDownLeft` `RotateInDownRight` `RotateInUpLeft` `RotateInUpRight`

`RotateOut` `RotateOutDownLeft` `RotateOutDownRight` `RotateOutUpLeft` `RotateOutUpRight`

#### Slide
`SlideInLeft` `SlideInRight` `SlideInUp` `SlideInDown`

`SlideOutLeft` `SlideOutRight` `SlideOutUp` `SlideOutDown`

#### Zoom
`ZoomIn` `ZoomInDown` `ZoomInLeft` `ZoomInRight` `ZoomInUp`

`ZoomOut` `ZoomOutDown` `ZoomOutLeft` `ZoomOutRight` `ZoomOutUp`