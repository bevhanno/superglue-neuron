# SuperGlue Neuron

## 1. Environment Setup

Follow the torch-neuronx install instructions from the [official documentation](https://awsdocs-neuron.readthedocs-hosted.com/en/latest/general/setup/neuron-setup/pytorch/neuronx/ubuntu/torch-neuronx-ubuntu22.html#setup-torch-neuronx-ubuntu22):

- Launch EC2 instance
- Install drivers and tools
- Install PyTorch Neuron (torch-neuronx)

## 2. Install Dependencies

Clone the original SuperGlue repository:

```bash
git clone https://github.com/magicleap/SuperGluePretrainedNetwork
```

Install SuperGlue dependencies:

```bash
cd superglue-neuron
pip install -r requirements.txt
```

## 3. Execute Benchmark

Open the `superglue_benchmark.ipynb` notebook and execute all cells.