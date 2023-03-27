# cycleLayoutManager

脱胎于LinaerLayoutManager的无限循环线性布局自定义Recycler.layoutManager


## 使用：


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
  
