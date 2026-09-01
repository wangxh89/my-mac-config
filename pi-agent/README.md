
```sh 
❯ cd ~/.pi/agent
❯ cat -p models.json
{
      "providers": {
            "whalecloudllm": {
                  "baseUrl": "https://lab.custom.com/gpt-proxy/v1",
                  "api": "openai-completions",
                  "apiKey": "ailab_eyViRsV4vi7sctS/kTGBe6AljGTZ0aYCNMrODIO1hiZ3MvCvHDoOxWIPuE6eKg1Eo2CINuiZepYep3j9Jo9wXmhY67e3Q6Soj2TNQE2kns=",
                  "models": [
                        {
                              "id": "b-gpt-5.6-sol-fast",
                              "name": "b-gpt-5.6-sol-fast(custom)",
                              "reasoning": false,
                              "input": [
                                    "text"
                              ],
                              "contextWindow": 128000,
                              "maxTokens": 32000,
                              "cost": {
                                    "input": 0,
                                    "output": 0,
                                    "cacheRead": 0,
                                    "cacheWrite": 0
                              }
                        }
                  ]
            }
      }
}




```