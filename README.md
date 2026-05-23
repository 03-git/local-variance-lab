# variance-lab

Data and harness for empirical local LLM measurement. 105,000+ inferences across 28 models.

Findings: https://jnous.com

## Structure

```
findings/       17 numbered findings (.txt)
data/           experiment datasets, raw eval JSON
prompts/        task-class prompt files
output/         raw run results
```

## Usage

```bash
./run-local-batch.sh --passes 5
python3 aggregate-local.py output/run-YYYYMMDD-HHMMSS 5
```

## License

GPLv2
