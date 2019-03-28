# Android Navigation Component

## Setup Project
import navigation library ใน project

```dependencies
dependencies {
    def nav_version = "2.1.0-alpha01"

    implementation "androidx.navigation:navigation-fragment:2.0.0" // For Navigation fragment
    implementation "androidx.navigation:navigation-ui:2.0.0" // For Navigation ui
}
```

## Create a navigation graph
1. ใน folder project คลิ๊กขาวที่ **New > Android Resource File**
2. ตั้งชื่อใน **File name** เช่น nav_graph
3. ใน **Resource type** ให้เลือกเป็น **Navigation**