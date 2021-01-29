| Task                      |       Metric         | Receptive Field Density |   Result    |    Log                              |  Json Logs                     |
|---------------------------|----------------------|-------------------------|-------------|-------------------------------------|--------------------------------|
| cola                      | matthews correlation | 1.0                     |  56.53      | Huggingface                         |                                | 
|                           |                      | 1.0                     |  54.95      |                                     |                                |
|                           |                      | 0.1                     |  51.27      | [0.1.txt](cola/log_density_0.1.txt) | [cola/json/0.1](cola/json/0.1) |
|                           |                      | 0.2                     |  51.80      | [0.2.txt](cola/log_density_0.2.txt) | [cola/json/0.2](cola/json/0.2) |
|                           |                      | 0.3                     |  49.23      | [0.3.txt](cola/log_density_0.3.txt) | [cola/json/0.3](cola/json/0.3) |
| sst2                      | accuracy             | 1.0                     |  92.32      | Huggingface                         |                                |
|                           |                      | 1.0                     |  92.09      |                                     |                                |
|                           |                      | 0.1                     |  91.06      | [0.1.txt](sst2/log_density_0.1.txt) | [sst2/json/0.1](sst2/json/0.1) |
|                           |                      | 0.2                     |  92.09      | [0.2.txt](sst2/log_density_0.2.txt) | [sst2/json/0.2](sst2/json/0.2) |
|                           |                      | 0.3                     |  91.97      | [0.3.txt](sst2/log_density_0.3.txt) | [sst2/json/0.3](sst2/json/0.3) |
| mrpc                      | accuracy/f1          | 1.0                     | 84.07/88.85 | Huggingface                         |                                |
|                           |                      | 1.0                     | 83.82/88.58 |                                     |                                |
|                           |                      | 0.1                     | 83.58/88.31 | [0.1.txt](mrpc/log_density_0.1.txt) | [mrpc/json/0.1](mrpc/json/0.1) |
|                           |                      | 0.2                     | 83.58/88.39 | [0.2.txt](mrpc/log_density_0.2.txt) | [mrpc/json/0.2](mrpc/json/0.2) |
|                           |                      | 0.3                     | 83.58/88.39 | [0.3.txt](mrpc/log_density_0.3.txt) | [mrpc/json/0.3](mrpc/json/0.3) |
| stsb                      | pearson/spearmanr    | 1.0                     | 88.64/88.48 | Huggingface                         |                                |
|                           |                      | 1.0                     | 88.83/88.68 |                                     |                                |
|                           |                      | 0.1                     | 64.05/67.01 | [0.1.txt](stsb/log_density_0.1.txt) | [stsb/json/0.1](stsb/json/0.1) |
|                           |                      | 0.2                     | 80.94/79.87 | [0.2.txt](stsb/log_density_0.2.txt) | [stsb/json/0.2](stsb/json/0.2) |
|                           |                      | 0.3                     | 84.80/83.84 | [0.3.txt](stsb/log_density_0.3.txt) | [stsb/json/0.3](stsb/json/0.3) |
| qqp                       |                      |                         |             |                                     |                                |
| mnli                      | accuracy             | 1.0                     | 83.91/84.10 | Huggingface                         |                                |
|                           |                      | 1.0                     | 84.48       |                                     |                                |
|                           |                      | 0.1                     | 82.64       | [0.1.txt](mnli/log_density_0.1.txt) | [mnli/json/0.1](mnli/json/0.1) |
|                           |                      | 0.2                     | 84.10       | [0.2.txt](mnli/log_density_0.2.txt) | [mnli/json/0.2](mnli/json/0.2) |
|                           |                      | 0.3                     |             |                                     | [mnli/json/0.3](mnli/json/0.3) |
| qnli                      | accuracy             | 1.0                     | 90.66       | Huggingface                         |                                |
|                           |                      | 1.0                     | 90.68       |                                     |                                |
|                           |                      | 0.1                     | 90.37       | [0.1.txt](qnli/log_density_0.1.txt) | [qnli/json/0.1](qnli/json/0.1) |
|                           |                      | 0.2                     | 90.72       | [0.2.txt](qnli/log_density_0.2.txt) | [qnli/json/0.2](qnli/json/0.2) |
|                           |                      | 0.3                     | 90.66       | [0.3.txt](qnli/log_density_0.3.txt) | [qnli/json/0.3](qnli/json/0.3) |
| rte                       | accuracy             | 1.0                     | 65.70       | Huggingface                         |                                |
|                           |                      | 1.0                     | 66.79       |                                     |                                |
|                           |                      | 0.1                     | 66.06       | [0.1.txt](rte/log_density_0.1.txt)  | [rte/json/0.1](rte/json/0.1)   |
|                           |                      | 0.2                     | 66.06       | [0.2.txt](rte/log_density_0.2.txt)  | [rte/json/0.2](rte/json/0.2)   |
|                           |                      | 0.3                     | 63.54       | [0.3.txt](rte/log_density_0.3.txt)  | [rte/json/0.3](rte/json/0.3)   |
| wnli                      | accuracy             | 1.0                     | 56.34       | Huggingface                         |                                |
|                           |                      | 1.0                     | 54.93       |                                     |                                |
|                           |                      | 0.1                     | 56.34       | [0.1.txt](wnli/log_density_0.1.txt) | [wnli/json/0.1](wnli/json/0.1) |
|                           |                      | 0.2                     | 54.93       | [0.2.txt](wnli/log_density_0.2.txt) | [wnli/json/0.2](wnli/json/0.2) |
|                           |                      | 0.3                     | 54.93       | [0.3.txt](wnli/log_density_0.3.txt) | [wnli/json/0.3](wnli/json/0.3) |


## Reading JSON files

```
import json


with open('sst2/json/0.1/val_0.json') as f:
    distillation = json.load(f)


step = 0 # classification task
print (f'When generating {distillation["true_target_label"]}')
attended_source = [f'{idx}:' + "'" + distillation['source_tokens_text'][idx] + "'" for idx in distillation['all_unmasked_source_tokens'][step]]
source = [f'{idx}:' + "'" + distillation['source_tokens_text'][idx] + "'" for idx in range(len(distillation['source_tokens_text']))]
print(f'  Source: {", ".join(source)}')
print("  Attended to source: {}".format(", ".join(attended_source)))

log = distillation['distillation'][0]['log']

top_labels = log[0]['model_top_predictions']
top_ps = log[0]['model_top_probs']
gold = [f'{label}: {p}' for label, p in zip(top_labels, top_ps)]
print (f' ** full model prediction: {", ".join(gold)}')
for l in log:
    top_labels = l['distilled_top_predictions']
    top_ps = l['distilled_top_probs']
    top_preds = [f'{label}: {p}' for label, p in zip(top_labels, top_ps)]
    print (f'  **added token: {l["added_token_text"]}, KL becomes {l["kl"]}, distillation top predictions: {", ".join(top_preds)}')
```
