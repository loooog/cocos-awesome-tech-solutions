* 目前 3.0.0 ~ 3.4.0 版本还不支持 jsb.saveImageData , 引擎计划在 3.5.0 支持, 要保存 imageData 为本地 png 文件需要参考下方的 pr 定制引擎
* https://gitee.com/zzf2019/engine-native/commit/1ddb6ec9627a8320cd3545d353d8861da33282a8 （此 pr 只支持保存 png ，且只支持 ios、android）
* 3.4.0 也还存在一个 readPixels 的 bug ，记得手动合并下 pr : https://github.com/cocos-creator/engine/pull/9900/files 

