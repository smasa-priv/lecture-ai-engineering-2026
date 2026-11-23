# 演習・宿題 RAG_TOP_K 比較結果

演習結果（`RAG_TOP_K = 5`）と宿題結果（`RAG_TOP_K = 8`）を比較した共有内容です。

- 比較内容: https://chatgpt.com/s/t_6b03b26f25448191b5b340103da57874

比較対象:

1. `uv run python -m app.agent --full-context --trace "$AIE_QUESTION"`
2. `uv run python -m app.retrieval "LoRA QLoRA 違い"`
3. `uv run python -m app.agent --trace "$AIE_QUESTION"`
4. `uv run python -m app.agent --tree --trace "$AIE_QUESTION"`
5. `uv run python -m app.agent --graph --trace "$AIE_QUESTION"`
