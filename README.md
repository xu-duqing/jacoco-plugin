## jacoco-plugin
Android Unit Test 开启测试覆盖率统计的脚本，不用关心应该如何配置。使用简单
## 使用
```
apply plugin: 'com.android.application'
apply from: 'https://raw.githubusercontent.com/xu-duqing/jacoco-plugin/master/jacoco-plugin.gradle'
```

### 执行
```
./gradlew jacocoTestReport
```

### 查看覆盖率
执行成功后会在生成目录 app/build/reports/jacoco 

使用浏览器打开index.html
