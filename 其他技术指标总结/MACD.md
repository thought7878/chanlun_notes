# MACD

## 一、MACD 由来:

MACD(Moving Average Convergence and Divergence)是 Geral Appel 于 1979 年提出的，它是一项利用短期(常用为 12 日)移动平均线与长
期(常用为 26 日)移动平均线之间的聚合与分离状况，对买进、卖出时机作出研判的技术指标。

## 二、MACD 指标的原理:

1. MACD 指标由双移动平均线发展而来，根据均线的构造原理，对价格的收盘价进行平滑处理，求出算术平均值以后再进行计算，是一种趋向
   类指标。
2. MACD 指标是运用快速(短期)和慢速(长期)移动平均线及其聚合与分离的征兆，加以双重平滑运算。
3. 根据移动平均线原理发展出来的 MACD，一则去除了移动平均线频繁发出假信号的缺陷，二则保留了移动平均线的效果，因此，MACD 指标具有均线趋势性、稳重性、安定性等特点，是用来研判买卖时机，预测价格涨跌的技术分析指标 。
4. MACD 指标主要是通过 EMA、DIF 和 DEA(或叫 MACD、DEM)这三值之间关系的研判，DIF 和 DEA 连接起来的移动平均线的研判以及 DIF 减去 DEM 值而绘制成的柱状图(BAR)的研判等来分析判断行情，预测走势中短期趋势的主要的股市技术分析指标。

其中，DIF 是核心，DEA 是辅助。
DIF 是快速平滑移动平均线(EMA1)和慢速平滑移动平均线(EMA2)的差。
BAR 柱状图在股市技术软件上是用红柱和绿柱的收缩来研判行情。

## 三、MACD 指标公式:

DIF:EMA(CLOSE,12)-EMA(CLOSE,26);
DEA:EMA(DIF,9);
MACD:(DIF-DEA)\*2,COLORSTICK;
1、 DIF 线(Difference):收盘价短期、长期指数平滑移动平均线间的差;
2、 DEA 线(Difference Exponential Average):DIF 线的 M 日指数平滑移动平均线;
3、 MACD 线:DIFF 线与 DEA 线的差，彩色柱状线;
