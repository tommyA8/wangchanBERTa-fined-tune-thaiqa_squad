# wangchanBERTa-fined-tune-thaiqa_squad
This is the wangchanberta-base-att-spm-uncased model, fine-tuned using the thaiqa_squad dataset.

# Try it out
https://huggingface.co/Thammarak/wangchanBERTa-QA-thaiqa_squad

# Load model directly
from transformers import AutoTokenizer, AutoModelForQuestionAnswering

tokenizer = AutoTokenizer.from_pretrained("Thammarak/wangchanBERTa-QA-thaiqa_squad")
model = AutoModelForQuestionAnswering.from_pretrained("Thammarak/wangchanBERTa-QA-thaiqa_squad")
