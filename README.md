# Lectures
This repo contains my notes following Andrej Karpathy's [Neural Networks: Zero to Hero](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) playlist. 



<a href="https://karpathy.ai/"><img src="sensei.jpeg" alt="karpathy" width="600"/></a>



| Repo | YouTube Video | Topics |
| -- | -- | -- |
| [micrograd](micrograd/micrograd_from_scratch.ipynb) | [The spelled-out intro to neural networks and backpropagation: building micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=1) | backpropagation, neural nets |
| [makemore part 1](makemore/part_1_bigrams.ipynb) | [The spelled-out intro to language modeling: building makemore](https://www.youtube.com/watch?v=PaCmpygFfXo&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=2) | bigram character-level language models with and without neural nets|
| [makemore part 2](makemore/part_2_MLP.ipynb)| [Building makemore Part 2: MLP](https://www.youtube.com/watch?v=TCH_1BHY58I&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=3) | MLPs, embeddings |
| [makemore part 3](makemore/part_3_MLPs2.ipynb) | [Building makemore Part 3: Activations & Gradients, BatchNorm](https://www.youtube.com/watch?v=P6sfmUTpUmc&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=4) | -- |
| N/A | [Building makemore Part 4: Becoming a Backprop Ninja](https://www.youtube.com/watch?v=q8SA3rM6ckI&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=5) | -- |
| N/A | [Building makemore Part 5: Building a WaveNet](https://www.youtube.com/watch?v=t3YJ5hKiMQ0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=6) | -- |
| N/A | [Let's build GPT: from scratch, in code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=7) | -- |
| [minbpe](minbpe/bpe.ipynb) | [Let's build the GPT Tokenizer](https://www.youtube.com/watch?v=zduSFxRajkE&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=9) | SolidGoldMagikarp, tokenization, byte pair encoding |



---
## Set up Conda Environment

```sh
conda create --name z2h python=3.11 -y
conda activate z2h
pip install -r requirements.txt
```

## Delete Conda Environment

```sh
conda deactivate
conda env remove --name z2h
```
