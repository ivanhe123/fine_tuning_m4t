# fine_tuning_m4t
Finetuning M4T using expanded fleurs dataset (zh to en version).

Using [customized seamless communication github repo](https://github.com/ivanhe123/seamless_communication/blob/main/src/seamless_communication/datasets/huggingface.py) to generate expanded fleurs data.

Fleurs dataset are expanded by [concatenating the text and audio of two samples to each other](https://github.com/ivanhe123/seamless_communication/blob/a850561daf4bb700d9c79f9925681535de3ff525/src/seamless_communication/datasets/huggingface.py#L105C1-L125C18) (default secondary data is [1/10 smaller](https://github.com/ivanhe123/seamless_communication/blob/a850561daf4bb700d9c79f9925681535de3ff525/src/seamless_communication/datasets/huggingface.py#L116) than the primary).
