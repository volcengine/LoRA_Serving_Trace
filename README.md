## LoRA Serving Trace

This repo contains the statistics of 126 LoRA inference services within one day. All data is at a 1 - minute granularity. The metrics include:
1. [Request rate](./normalized_qps.csv)
2. [Average input token length](./normalized_avg_prompt.csv)
3. [Average output token length](./normalized_avg_output.csv)
4. [Total input token number](./normalized_prompt_sum.csv)
5. [Total output token number](./normalized_output_sum.csv)
6. [Input token number percentiles](./normalized_prompt_percentiles.csv)
7. [Output token number percentiles](./normalized_output_percentiles.csv)

All data has been normalized. Only relative values are included.