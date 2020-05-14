邊緣偵測（利用cnn kernal實現不同效果）
====
kernal 使用<br>
`kernely = np.array([[1,0,-1],[2,0,-2],[1,0,-1]])`<br>
`kernelx = np.array([[1,2,1],[0,0,0],[-1,-2,-1]])`<br>
原圖：<br>
<img src="https://github.com/buloobuloo/Visual/blob/master/%E9%82%8A%E7%B7%A3%E5%81%B5%E6%B8%AC/IMG_6900.jpeg"><br>
效果y：<br>
<img src="https://github.com/buloobuloo/Visual/blob/master/%E9%82%8A%E7%B7%A3%E5%81%B5%E6%B8%AC/Edgwx.jpg"><br>
效果x：<br>
<img src="https://github.com/buloobuloo/Visual/blob/master/%E9%82%8A%E7%B7%A3%E5%81%B5%E6%B8%AC/Edgwy.jpg">
<br>
參考資料：<br>
1.<a href="https://medium.com/%E9%9B%9E%E9%9B%9E%E8%88%87%E5%85%94%E5%85%94%E7%9A%84%E5%B7%A5%E7%A8%8B%E4%B8%96%E7%95%8C/%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92-ml-note-convolution-neural-network-%E5%8D%B7%E7%A9%8D%E7%A5%9E%E7%B6%93%E7%B6%B2%E8%B7%AF-bfa8566744e9">CNN實作</a>
<br>
2.<a href="https://github.com/mysterio42/Custom-Conv2D">kernal 差別效果</a>
