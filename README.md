# Screen adaptation
android screen adaptation<br>
api 'com.gonghui.screen:screen-adaptation:1.0'<br>

以320dp为基础倍率<br>
1.使用@dimen/dp5 @dimen/dp10等代替原来的5dp 10dp<br>
2.在Java中，用getResources().getDimension(R.dimen.dp5)来获取像素，再进行dp或sp的转换
