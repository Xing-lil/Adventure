#Unity2D Tips 
  
###1. 状态（动画）切换时，根据情况勾选HasExitTime——选中表示当前动画播放完成后才可切换状态；
###2. ExitTime是百分比，范围0~1；
###3. 可在代码中指定父子级对象，使用Transform实现；
###4. 使用Physical2D.Linecast()检测起点与目标点的直线上是否有碰撞体，注意先禁用自身碰撞器，检测完毕后复原；  
###5. 可使用刚体的MovePosition方法实现位移，注意简单地配合使用Vector2.Lerp()函数并不能实现匀速运动；
###6. 使用Debug.log输出调试日志；
###7. 使用Animation的setTrigger()切换动画状态；
###8. 使用OnLevelWasLoaded函数加载关卡，并使用脚本保存关键数值；
