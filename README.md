# cycleLayoutManager

脱胎于LinaerLayoutManager的线性布局自定义Recycler.layoutManager,可以使得item无限循环。

## 预览效果
<div align=center> <img src="https://github.com/aFlyFatPig/hello-world/blob/34aac198edff40876fdef4463ba4b2ee2f37f1a5/gif.gif" ```
width = "200" height = "400"``` /> </div>


#### root build.gradle添加（仓库依赖）：
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  
#### 需要的模块的build.gradle添加(项目依赖)：
    dependencies {
	        implementation 'com.github.aFlyFatPig:cycleLayoutManager:1.0.0'
	}
  
  
#### 和LinearLayoutManager一样使用

       CycleLayoutManager layoutManager =  new CycleLayoutManager();
       layoutManager.setOrientation(RecyclerView.HORIZONTAL/VERTICAL);
       recyclerView.setLayoutManager(layoutManager);
  
