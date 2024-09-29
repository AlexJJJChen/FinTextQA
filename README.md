# FinTextQA
Thank you for your attention to this dataset. Unfortunately, I am sorry to inform you that the legal department at HSBC has not granted permission to open source the dataset. However, I would be happy to provide details on how we collected the data if you are interested. Send me an email via jchen524@connect.hkust-gz.edu.cn

## Requirements


To create an environment with [MiniConda](https://docs.anaconda.com/free/miniconda/) and activate it.

```bash
conda create -n fintextqa python==3.10
conda activate fintextqa
pip install -r requirements.txt
```

## Usage
If you want to get evidence from document, please run the following code:
```bash
python get_evidence.py

```
If you want to get response from document, please run the following code:
```bash
python get_response.py

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
