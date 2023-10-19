Finetune BERT for Tech Product Names Named Entity Recognition (NER)

This NER model can recognize and tag tech product names like 'Asus ZenBook UX430UN', 'Acer Aspire 3', 'Nokia 110 4G', or 'Xiaomi 11T Pro 5G Hyperphone' in a sentence.
The model was trained on the names of laptops and mobile phones. It might not be suitable for other tech products. 

The training data was generated with GPT-4 via OpenAI API. See the following Colab Notebook for a tutorial on how to generate training data with GPT-4. 

Model Link & API Demo: https://huggingface.co/ashleyliu31/bert-finetuned-tech-product-name-ner

Colab Notebook: https://colab.research.google.com/drive/1gOOWK_Zt4wnoZLEyeNm4p-9iZb_Vz7co?usp=sharing

Dataset: https://huggingface.co/datasets/ashleyliu31/tech_product_names_ner

Credits to NielsRogge for the part on training: https://github.com/NielsRogge/Transformers-Tutorials/blob/master/BERT/Custom_Named_Entity_Recognition_with_BERT.ipynb
