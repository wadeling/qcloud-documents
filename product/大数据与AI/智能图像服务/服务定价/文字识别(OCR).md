##   计费方式
腾讯云文字识别（OCR）按照实际使用量付费，采用后付费方式，次月3-7日会出本月账单，进行账号扣费。
##   计费冻结机制

本月结算完成后，将以本月账单金额的120% 对帐户进行下月费用预估冻结。
下月结算时，先解冻上月的冻结费用，再进行本月使用额度的扣费。

##   OCR识别

图片OCR识别按照月接口调用采取阶梯到达计费方式，当月总量在哪个阶梯内，则按该阶梯单价计费，接口调用量越大，单价越低。

| 月接口调用总量 | 0<调用量≤1千 | 1千<调用量≤1万 | 1万<调用量≤10万 | 10万<调用量 |
| ------- | ------ | ------- | ------ | ----- |
| 身份证识别   | 0.2元/次   | 0.2元/次    | 0.12元/次  | 0.08元/次 |
| 名片识别    | 0.05元/次  | 0.05元/次   | 0.04元/次  | 0.02元/次 |
| 行驶证/驾驶证 | 0      | 0.2元/次    | 0.15元/次  | 0.08元/次 |
| 银行卡     | 0      | 0.2元/次    | 0.15元/次  | 0.08元/次 |
| 营业执照    | 0      | 0.2元/次    | 0.15元/次  | 0.08元/次 |
| 车牌      | 0      | 0.2元/次    | 0.15元/次  | 0.08元/次 |
| 通用印刷体识别 | 0      | 0.2元/次    | 0.15元/次  | 0.08元/次 |


><font color="#0000cc">**注意：** </font>
>  联系我们，请点击右侧【购买咨询】。

