# CococsCreator 技术方案分享

 技术方案来源自论坛、github 开源仓库、热心开发者、Cocos 引擎开发团队、cocos 技术支持团队。

---
*技术支持团队提供：*

* (v3.3.2) 2D 光照

  > 工程 git 仓库地址: 
  > https://github.com/cocos-creator/CococsCreator-public-technology-solutions/tree/main/demo/Creator3.3.2_2D_Light
  >
  > 素材来自: 
  > https://www.codeandweb.com/blog/2015/05/12/lighting-demo-cocos2d-x
  > https://github.com/CodeAndWeb/cocos2d-x-dynamic-lighting

  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/gif/2021111101.gif)

  

* (v3.3.2) 2D 阴影

  > 工程 git 仓库地址: 
  > https://github.com/cocos-creator/CococsCreator-public-technology-solutions/tree/main/demo/Creator3.3.2_2D_ShadowMap
  >
  > 素材来自: 
  > https://github.com/mattdesl/lwjgl-basics/wiki/2D-Pixel-Perfect-Shadows
  
  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/gif/2021111102.gif)



* (v3.3.0) spine 使用非图集纹理进行局部换装

  > 工程 git 仓库地址: 
  > https://github.com/cocos-creator/CococsCreator-public-technology-solutions/tree/main/demo/Creator3.3.0_2D_spine_changeSlot_with_texture
  
  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/gif/2021111103.gif)

* (v3.3.2) box2d性能优化(box2d wasm)

  > 工程 git 仓库地址: 
  > https://github.com/cocos-creator/CococsCreator-public-technology-solutions/tree/main/demo/Creator3.3.2_2D_Box2DJS_WebAssembly
  
  |  平台  |  优化前  | 优化后  |  性能比较  |
  | :-----------------------: | :-----------------------: | :-----------------------: | :-----------------------: |
  | macOS - Safari | ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111901.jpeg)   | ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111911.jpeg)   |  性能提升**50%**  |
  | Windows - Chrome |  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111902.jpeg)  |  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111912.jpeg)  |  性能提升**67%**  |
  | iOS - Safari |  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111903.jpeg)  | ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111913.jpeg)   | 性能提升**80%**  |
  | Android - Chrome |  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111904.jpeg)  |  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111914.jpeg)  | 性能提升**60%**  | 
  | iOS - WechatMiniGame |  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111905.jpeg)  |  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111915.jpeg)  | 性能提升**500%**  |  
  | Android - WechatMiniGame | ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111906.jpeg)   |  ![Image Text](https://github.com/cocos-creator/CococsCreator-public-technology-solutions/blob/main/image/2021111916.jpeg)  | 性能提升**125%**  |