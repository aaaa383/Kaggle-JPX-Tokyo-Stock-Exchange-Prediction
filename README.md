# Kaggle-JPX-Tokyo-Stock-Exchange-Prediction
<img width="800" alt="無題" src="https://user-images.githubusercontent.com/58076642/168525518-08b5f01a-7fe4-4b2a-8121-4c9609383aff.png">  

## コンペの目的  
日本取引所グループ（JPX）による、2000銘柄の証券を対象にした、証券の値段（終値）の変化率予測を予測する  
翌日から翌々日にかけての終値の変化率が目的変数   

## 評価指標  
日次スプレッドのシャープレシオによって算出される  
詳しい説明：(シャープレシオ)[https://en.wikipedia.org/wiki/Sharpe_ratio]  
実装コード：https://www.kaggle.com/code/smeitoma/jpx-competition-metric-definition

## Overview
Success in any financial market requires one to identify solid investments. When a stock or derivative is undervalued, it makes sense to buy. If it's overvalued, perhaps it's time to sell. While these finance decisions were historically made manually by professionals, technology has ushered in new opportunities for retail investors. Data scientists, specifically, may be interested to explore quantitative trading, where decisions are executed programmatically based on predictions from trained models.

There are plenty of existing quantitative trading efforts used to analyze financial markets and formulate investment strategies. To create and execute such a strategy requires both historical and real-time data, which is difficult to obtain especially for retail investors. This competition will provide financial data for the Japanese market, allowing retail investors to analyze the market to the fullest extent.

Japan Exchange Group, Inc. (JPX) is a holding company operating one of the largest stock exchanges in the world, Tokyo Stock Exchange (TSE), and derivatives exchanges Osaka Exchange (OSE) and Tokyo Commodity Exchange (TOCOM). JPX is hosting this competition and is supported by AI technology company AlpacaJapan Co.,Ltd.

This competition will compare your models against real future returns after the training phase is complete. The competition will involve building portfolios from the stocks eligible for predictions (around 2,000 stocks). Specifically, each participant ranks the stocks from highest to lowest expected returns and is evaluated on the difference in returns between the top and bottom 200 stocks. You'll have access to financial data from the Japanese market, such as stock information and historical stock prices to train and test your model.

All winning models will be made public so that other participants can learn from the outstanding models. Excellent models also may increase the interest in the market among retail investors, including those who want to practice quantitative trading. At the same time, you'll gain your own insights into programmatic investment methods and portfolio analysis―and you may even discover you have an affinity for the Japanese market.  

### 日本語(deepl)  
どのような金融市場でも、成功するためには、確かな投資対象を見極めることが必要です。株式やデリバティブが過小評価されている場合は、購入することが理にかなっています。割高であれば、売るべきでしょう。このような金融の判断は、これまで専門家が手作業で行ってきましたが、テクノロジーの進歩により、個人投資家にも新たな機会が訪れました。特にデータサイエンティストは、学習したモデルからの予測に基づいてプログラム上で意思決定を行う、定量取引に興味を持つかもしれません。

金融市場を分析し、投資戦略を策定するために使用される既存の定量取引の取り組みはたくさんあります。このような戦略を立て、実行するためには、過去とリアルタイムの両方のデータが必要ですが、特に個人投資家にとっては入手が困難です。今回のコンペティションでは、日本市場の金融データを提供することで、個人投資家が市場を最大限に分析することを可能にします。

株式会社日本取引所グループ（JPX）は、世界最大級の証券取引所である東京証券取引所、デリバティブ取引所の大阪取引所、東京工業品取引所を運営する持株会社です。本コンペティションは、JPXが主催し、AI技術企業のアルパカジャパン株式会社が協賛しています。

このコンペティションでは、学習段階が終了した後、実際の将来のリターンに対してモデルを比較します。コンペティションでは、予測対象銘柄（約2,000銘柄）からポートフォリオを構築します。具体的には、各参加者が期待リターンの高い銘柄から低い銘柄へと順位をつけ、上位200銘柄と下位200銘柄のリターンの差で評価されます。参加者は、日本市場の株式情報や過去の株価などの金融データにアクセスし、モデルの訓練と検証を行います。

受賞したモデルはすべて公開され、他の参加者が優れたモデルから学ぶことができます。また、優れたモデルは、クオンツ取引を実践したい人など、個人投資家の市場に対する関心を高める可能性があります。同時に、プログラムによる投資手法やポートフォリオ分析について自分なりの知見を得ることができ、日本市場に親近感を持つことができるかもしれません。  

