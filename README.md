# sample-codes-for-aiml
こちらでは AWS を使った AI/ML のサンプルコードを公開しています。

- amazon-rekognition-image-analysis
  - AWS SDK for Python を使って Amazon Rekognition で画像分析します
- amazon-sagemaker-jumpstart
  - Amazon SageMaker JumpStart に関するノートブックです
  - sagemaker-jumpstart-inference-local.ipynb: Amazon SageMaker JumpStart で学習させた PyTorch の VGG モデルを使ってローカルで推論するノートブック
- autogluon-tabular-customer-churn
  - [AutoGluon-Tabular](https://auto.gluon.ai/stable/tutorials/tabular_prediction/index.html) を使って顧客離反予測します
- deoldify-sagemaker
  - モノクロ画像をカラー化する [DeOldify](https://github.com/jantic/DeOldify) を Amazon SageMaker で使うノートブックです
- gnn-node-classification
  - GNN を使ってノード分類を行うサンプルです。
- lightgbm-byoc
  - Amazon SageMaker でカスタムコンテナで LightGBM を使うサンプルです。
    - lightGBM-byoc.ipynb: カスタムコンテナを使って学習とリアルタイム推論を行う方法を [公式のサンプルノートブック](https://github.com/aws-samples/amazon-sagemaker-script-mode/blob/master/lightgbm-byo/lightgbm-byo.ipynb) をベースに必要最小限な部分を抜き出して簡素化したノートブック
    - lightGBM-batch-inference.ipynb: Transform API と Amazon SageMaker Processing それぞれを使ってバッチ推論を行うノートブック
- mlops
  - step-functions-model-train-evaluate-pipeline: AWS Step Functions Data Science SDK, Amazon SageMaker, Amazon SageMaker Experiments を使ってデータの前処理、モデルの学習、モデルの評価を行うパイプラインを作成するノートブック
- multi-model-endpoint
  - SageMaker のマルチモデルエンドポイント（1つのエンドポイントに複数のモデルをデプロイする機能）でモデルをホスティングします
- similar-image-search
  - MXNet の学習済みモデルと Amazon Elasticsearch Service を使って類似画像検索します
- tensorflow2-mnist-byom
  - Amazon SageMaker の機能を使って Tensorflow2 のモデルを学習、デプロイします
