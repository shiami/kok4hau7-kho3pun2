# 國校仔課本

* 版本比較
 * [線上網站](http://210.240.194.93/nttu/khopun/bang-cham/)
 * 也參考允言老師主機[ip093](https://github.com/Taiwanese-Corpus/Ungian_Tsu2-ki1#ip093)的程式和檔案
 
## 原始資料
* 楊允言老師提供的檔案
* doc裡有固定的表格格式

## JSON格式資料
* `原始資料`經[轉換工具](https://github.com/sih4sing5hong5/KIPsupin_doc2yaml)處理成`json`格式
* 格式請[參考](https://github.com/sih4sing5hong5/KIPsupin_doc2yaml#%E6%95%99%E8%82%B2%E9%83%A8%E8%87%BA%E7%81%A3%E9%96%A9%E5%8D%97%E8%AA%9E%E5%AD%97%E8%A9%9E%E9%A0%BB%E8%AA%BF%E6%9F%A5%E5%B7%A5%E4%BD%9C%E8%B3%87%E6%96%99%E8%BD%89%E6%8F%9B%E5%B7%A5%E5%85%B7)

## 產生臺灣言語資料yaml格式
```
virtualenv --python python3 venv
source venv/bin/activate
pip install --upgrade pip
pip install KIPsupin-doc2yaml
全部json敆做yaml 臺語國校仔課本
npm i && npm run deploy
```
就會使掠[yaml](https://taiwanese-corpus.github.io/kok4hau7-kho3pun2/臺語國校仔課本.yaml)矣
