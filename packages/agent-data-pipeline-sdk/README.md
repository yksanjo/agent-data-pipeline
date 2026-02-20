# agent-data-pipeline-sdk

> Package 3: sdk for Automated Data Pipeline Builder

## Installation

```bash
npm install @agent-data-pipeline/agent-data-pipeline-sdk
```

## Usage

```javascript
import { AgentDataPipelineSdk } from '@agent-data-pipeline/agent-data-pipeline-sdk';

const service = new AgentDataPipelineSdk();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
