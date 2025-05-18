# Chinese Sentence–Keyword Dataset for Keyword Generation

This dataset is designed for training and evaluating Chinese keyword generation models based on sequence-to-sequence architectures such as BART.

---

## Dataset Format

The dataset is stored as a single JSON file, where each entry is a mapping from a Chinese sentence (user comment or post) to a list of semantic keywords.

```json
{
  "这款手机性价比很高，值得购买。": "性价比 购买 值得",
  "我认为未来新能源车会成为主流。": "新能源车 主流 趋势",
  ...
}
