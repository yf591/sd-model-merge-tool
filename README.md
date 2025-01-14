# sd-model-merge-tool

This repository contains a collection of Google Colab notebooks for merging Stable Diffusion models and LoRAs. It supports various merging methods and source types.

## Disclaimer

*   This code is provided **as is**, without any warranty.
*   The user assumes all responsibility for any damages that may arise from using this code.
*   **The user is solely responsible for the results of the merged models.**
*   **Exercise caution when using or distributing merged models, as some may have licenses that restrict usage.**
*   **Always verify the license information for each model, and adhere to their terms of service.**
*   **This code does not guarantee that all models can be used within their respective license terms.**

## License

This code is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/), with the following additional restriction:

*   **You are not allowed to sell this code (or modified versions of it).**

This means:

*   **Attribution:** You must give appropriate credit to the original author when distributing modified versions.
*   **ShareAlike:** If you modify this code, you must distribute your contributions under the same license (including the additional restriction against selling the code).
*   You are free to share and adapt the material under the terms of this license, for both commercial and non-commercial use.
    * Note: You are free to utilize the merged model for both commercial and non-commercial use, however you cannot sell the code itself.

## Notebooks

This repository contains the following notebooks:

| Notebook                                          | Description                                                                                                | <div style="text-align: center;">GitHub Link</div>                                                                                                                              | <div style="text-align: center;">Colab Link</div>                                                                                                                                |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| `04_Merge_Model_Maker_Ver1_0_0.ipynb`             | Simple model merging for two models from Hugging Face.                                                    | <div style="text-align: center;">[<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20" height="20" alt="GitHub" />](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_0_0.ipynb)</div>  |  <div style="text-align: center;">[<img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="20" height="20" alt="Colab" />](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_0_0.ipynb)</div> |
| `04_Merge_Model_Maker_Ver1_0_1.ipynb`             | Simple model merging for two models from Hugging Face, Civitai, or MyDrive.                                | <div style="text-align: center;">[<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20" height="20" alt="GitHub" />](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_0_1.ipynb)</div>  |  <div style="text-align: center;">[<img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="20" height="20" alt="Colab" />](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_0_1.ipynb)</div> |
| `04_Merge_Model_Maker_Ver1_1_0.ipynb`             | Layered model merging for two models from Hugging Face.                                                  | <div style="text-align: center;">[<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20" height="20" alt="GitHub" />](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_1_0.ipynb)</div>  |  <div style="text-align: center;">[<img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="20" height="20" alt="Colab" />](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_1_0.ipynb)</div> |
| `04_Merge_Model_Maker_Ver1_1_1.ipynb`             | Layered model merging for two models from Hugging Face, Civitai, or MyDrive.                              | <div style="text-align: center;">[<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20" height="20" alt="GitHub" />](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_1_1.ipynb)</div>  |  <div style="text-align: center;">[<img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="20" height="20" alt="Colab" />](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver1_1_1.ipynb)</div> |
| `04_Merge_Model_Maker_Ver2_0_0.ipynb`             | Simple model merging for three or more models from Hugging Face, Civitai, or MyDrive.                                        | <div style="text-align: center;">[<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20" height="20" alt="GitHub" />](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver2_0_0.ipynb)</div>  |  <div style="text-align: center;">[<img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="20" height="20" alt="Colab" />](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver2_0_0.ipynb)</div> |
| `04_Merge_Model_Maker_Ver2_1_0.ipynb`             | Layered model merging for three or more models from Hugging Face, Civitai, or MyDrive.                     | <div style="text-align: center;">[<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20" height="20" alt="GitHub" />](https://github.com/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver2_1_0.ipynb)</div>  |  <div style="text-align: center;">[<img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="20" height="20" alt="Colab" />](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/04_Merge_Model_Maker_Ver2_1_0.ipynb)</div> |
| `05_Merge_Lora_Model_Ver1_0_0.ipynb`              | Simple merging for two LoRA models from MyDrive.                                                         | <div style="text-align: center;">[<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20" height="20" alt="GitHub" />](https://github.com/yf591/sd-model-merge-tool/blob/main/05_Merge_Lora_Model_Ver1_0_0.ipynb)</div>   |  <div style="text-align: center;">[<img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="20" height="20" alt="Colab" />](https://colab.research.google.com/github/yf591/sd-model-merge-tool/blob/main/05_Merge_Lora_Model_Ver1_0_0.ipynb)</div>  |


## Usage

1.  Open the desired notebook in Google Colab.
2.  Follow the instructions within the notebook to load and merge your models or LoRAs.
3.  Adjust the merging parameters as needed.
4.  Save the merged model to your Google Drive.

## Notes

*   The performance may vary depending on Google Colab's utilization and available resources.
*   Downloading large models may take time.
*   Always review the output messages and make sure all dependencies are installed correctly.
*   Different models and merging parameters can produce varied results. Experiment to find the optimal settings for your use case.

## About Model and LoRA Licenses

*   Please check the license of each Stable Diffusion model or LoRA you use from the distribution source (Hugging Face, Civitai, etc.).
*   Please comply with the terms of use of each component and do not infringe on copyrights.
*   **This code does not guarantee that all models or LoRAs can be used within their respective license terms.**

## Acknowledgements

*   This code is provided by yf591.
*   We acknowledge the generous contributions of the model and LoRA creators for sharing their work.
