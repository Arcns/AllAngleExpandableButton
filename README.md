[![](https://www.jitpack.io/v/Arcns/AllAngleExpandableButton.svg)](https://www.jitpack.io/#Arcns/AllAngleExpandableButton)

### 感谢uin3566！相比[uin3566/AllAngleExpandableButton](https://github.com/uin3566/AllAngleExpandableButton) ,根据我的实际需求做了以下修改：
1. 修复无法支持透明图片的问题
2. 更改为androidx
3. 更新gradle版本

```
allprojects {
	repositories {
		...
		maven { url 'https://www.jitpack.io' }
	}
}
```
	
```
dependencies {
	implementation 'com.github.Arcns:AllAngleExpandableButton:Tag'
}
```

使用方法请查阅[uin3566/AllAngleExpandableButton](https://github.com/uin3566/AllAngleExpandableButton)
