### MaterialDesign使用简介
#### 使用主题

```
<style name="AppTheme" parent="@android:style/Theme.Material">
<!--ActionBar的颜色-->
<item name="android:colorPrimary">#0f0</item>
<!--状态栏的颜色-->
<item name="android:colorPrimaryDark">#00f</item>
<!--控件的颜色-->
<item name="android:colorAccent">#f00</item>
```

### 材料设计中的阴影特效

```
Elevation:高度，静态属性 一般设置之后就不动了
TranslationZ：Z轴相对于高度的位置，用于实现动画的动态属性 动态属性一般会再去设置
Z = Elevation + TranslationZ；
```
