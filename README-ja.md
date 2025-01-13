# sd-model-merge-tool

このリポジトリには、Stable DiffusionモデルとLoRAをマージするためのGoogle Colabノートブックのコレクションが含まれています。さまざまなマージ方法とソースタイプをサポートしています。

## 免責事項

*   このコードは**現状のまま**提供され、一切の保証をしません。
*   このコードの利用によって生じたいかなる損害についても、一切の責任を負いません。
*   **マージされたモデルの結果に関する責任は、すべて利用者自身にあります。**
*   **マージされたモデルを使用または配布する際は、使用を制限するライセンスが含まれている可能性があるため、注意してください。**
*   **各モデルのライセンス情報を必ず確認し、利用規約を遵守してください。**
*   **本コードは、すべてのモデルがそれぞれのライセンス条項内で利用できることを保証するものではありません。**

## ライセンス

このコードは、[Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/) の下で提供されています。ただし、以下の追加条項が適用されます。

*   **本コード（または改変版）の販売は許可されません。**

これは以下のことを意味します。

*   **表示 (Attribution, BY):**  改変版を配布する際は、元の作者を適切にクレジット表示する必要があります。
*   **継承 (ShareAlike, SA):**  このコードを改変したものを配布する際は、元のライセンス（コードの販売禁止を含む）と同じライセンスを適用する必要があります。
*   このライセンスの条項に従い、商用または非商用目的で素材を自由に共有および翻案できます。
    * 注意: マージされたモデルは商用・非商用を問わず自由に使用できます。ただし、コード自体を販売することはできません。

## ノートブック一覧

このリポジトリには、以下のノートブックが含まれています。

| ノートブック                                   | 説明                                                                                              | GitHubリンク                                                                                                                                | Colabリンク                                                                                                                                |
| :--------------------------------------------- | :------------------------------------------------------------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| `04_Merge_Model_Maker_Ver1_0_0.ipynb`           | Hugging Faceの2つのモデルの単純なマージ用。                                                        | [GitHubリンク](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_0_0.ipynb)                                    | [Colabリンク](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_0_0.ipynb)                         |
| `04_Merge_Model_Maker_Ver1_0_1.ipynb`           | Hugging Face、Civitai、またはMyDriveの2つのモデルの単純なマージ用。                                | [GitHubリンク](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_0_1.ipynb)                                    | [Colabリンク](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_0_1.ipynb)                         |
| `04_Merge_Model_Maker_Ver1_1_0.ipynb`           | Hugging Faceの2つのモデルの階層マージ用。                                                         | [GitHubリンク](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_1_0.ipynb)                                    | [Colabリンク](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_1_0.ipynb)                         |
| `04_Merge_Model_Maker_Ver1_1_1.ipynb`           | Hugging Face、Civitai、またはMyDriveの2つのモデルの階層マージ用。                                | [GitHubリンク](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_1_1.ipynb)                                    | [Colabリンク](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_1_1.ipynb)                         |
| `04_Merge_Model_Maker_Ver2_0_0.ipynb`           | Hugging Faceの3つ以上のモデルの単純なマージ用。                                                       | [GitHubリンク](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver2_0_0.ipynb)                                    | [Colabリンク](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver2_0_0.ipynb)                         |
| `04_Merge_Model_Maker_Ver2_1_0.ipynb`           | Hugging Face、Civitai、またはMyDriveの3つ以上のモデルの階層マージ用。                                | [GitHubリンク](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver2_1_0.ipynb)                                    | [Colabリンク](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver2_1_0.ipynb)                         |
| `05_Merge_Lora_Model_Ver1_0_0.ipynb`            | MyDriveの2つのLoRAモデルの単純なマージ用。                                                           | [GitHubリンク](https://github.com/yf591/sd-model-merge-tool/blob/main/05_Merge_Lora_Model_Ver1_0_0.ipynb)                                     | [Colabリンク](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/05_Merge_Lora_Model_Ver1_0_0.ipynb)                          |

## 使用方法

1.  Google Colabで目的のノートブックを開きます。
2.  ノートブック内の指示に従って、モデルまたはLoRAをロードしてマージします。
3.  必要に応じて、マージのパラメータを調整します。
4.  マージされたモデルをGoogleドライブに保存します。

## 注意点

*   パフォーマンスは、Google Colabの利用状況や利用可能なリソースによって異なる場合があります。
*   大きなモデルのダウンロードには時間がかかる場合があります。
*   常に出力メッセージを確認し、すべての依存関係が正しくインストールされていることを確認してください。
*   異なるモデルやマージパラメータは、さまざまな結果を生み出す可能性があります。実験して、ユースケースに最適な設定を見つけてください。

## モデルとLoRAのライセンスについて

*   Hugging Face、Civitaiなど、各モデルまたはLoRAの配布元から、ライセンスを確認してください。
*   各コンポーネントの利用規約を遵守し、著作権を侵害しないでください。
*   **本コードは、すべてのモデルまたはLoRAがそれぞれのライセンス条項内で利用できることを保証するものではありません。**

## 謝辞

*   このコードは yf591 が提供します。
*   モデルおよびLoRAの作成者が自身の作品を共有してくださっていることに感謝いたします。
