# fcitx5-android-flypyyx
供 fcitx5-android 使用的小鹤音形码表。

#fcitx5-android 下载

 https://github.com/fcitx5-android/fcitx5-android

#码表启用方法

 参考 https://fcitx5-android.github.io/faq

 flypyyx.dict 添加至 /Android/data/org.fcitx.fcitx5.android/files/data/table/
 
 flypyyx.conf 添加至 /Android/data/org.fcitx.fcitx5.android/files/data/inputmethod/

#自定义码表方法
 下载并编辑 小鹤音形for手机“搜狗”、“百度”自定义方案.txt
 
 来源 http://flypy.ysepan.com/
    
http://ys-f.ysepan.com/116124345/318994108/TW4SkJt732X5U3L5JLTN2c/%E5%B0%8F%E9%B9%A4%E9%9F%B3%E5%BD%A2for%E6%89%8B%E6%9C%BA%E2%80%9C%E6%90%9C%E7%8B%97%E2%80%9D%E3%80%81%E2%80%9C%E7%99%BE%E5%BA%A6%E2%80%9D%E8%87%AA%E5%AE%9A%E4%B9%89%E6%96%B9%E6%A1%88.txt

 在 linux 安装 libime-bin
 
 libime_tabledict flypyyx.txt flypyyx.dict
