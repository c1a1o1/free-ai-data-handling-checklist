# Free AI Data-Handling Checklist

No sign-up, no training, and no retention are three different claims. Audit the exact feature before pasting any work.

```csv
checked_at,tool,feature,account_scope,input_destination,third_party,retention_days,exception,training_default,opt_out_scope,deletion,policy_url,evidence
2026-11-22,Example Tool,text summary,anonymous,unknown,unknown,unknown,unknown,unknown,unknown,unknown,https://example.com/,fictional
```

- Use synthetic data only for tests. For restricted input stop unless destination, retention and approved-use terms cover the material. Web, API, and browser extensions can differ.
- Check whether a training control applies to a conversation, account or workspace, and whether feedback or third-party tools are exceptions.
- Separate deleting visible history from expiry in logs, backups and providers. Do not turn silence into zero retention.
- Example reading exercise: [OpenAI Temporary Chat FAQ](https://help.openai.com/en/articles/8914046-temporary-chat-faq) distinguishes training restrictions from retention. Check current terms rather than generalizing to other features.
