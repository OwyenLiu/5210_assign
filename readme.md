###  1. �����������ڱ���

���ԣ�
- universeΪ��֤500
- ��������Ϊfundamental & price volume
- ��Ƶ--ÿ�������һ�������յ���
- ��Ʊ��ղ���

���ӣ����ն�������ֵ���н��������õ�һ�����ʮ�鹹����ղ���
- last_tradeday_amount: ���һ�������յĳɽ���
- buffett_zscore���ͷ���ָ�꣨Buffett Indicator���г�����ֵ�� GDP ֮�ȣ��ı�׼��������z-score��
- momentum_21����ȥ21�������յĶ�������

![](pic_source/is_performance.png)
![](pic_source/is_corr.png)

###  2. ���������

�������Ǹ���is�������жϸ����ӻ������Ч��

Ϊ��ʹ��ϵ�����Ϊ�������Ƕ�is.sharpeΪ����last_tradeday_amount��momentum_21���������ף��������hedge_direction


#### 2.1 last_tradeday_amount
sharpe--returns--turnover--max_dd

0.8831605290401672 0.18625813972056435 1.036457966688697 -0.2947236261010202
![](pic_source/factor1.png)


#### 2.2 buffett_zscore
sharpe--returns--turnover--max_dd

0.6007194174636389 0.11943164058315031 0.5651585529205572 -0.5100253099077462
![](pic_source/factor2.png)


#### 2.3 momentum_21
sharpe--returns--turnover--max_dd

0.17499702992547306 0.036748604744499466 1.7139573699660593 -0.46383133553132494
![](pic_source/factor3.png)