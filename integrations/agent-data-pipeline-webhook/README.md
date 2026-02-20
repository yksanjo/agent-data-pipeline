# agent-data-pipeline-webhook

> Integration: webhook for Automated Data Pipeline Builder

## Installation

```bash
npm install @agent-data-pipeline/agent-data-pipeline-webhook
```

## Usage

```javascript
import { AgentDataPipelineWebhook } from '@agent-data-pipeline/agent-data-pipeline-webhook';

const service = new AgentDataPipelineWebhook();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
