# agent-data-pipeline-api

> Package 2: api for Automated Data Pipeline Builder

## Installation

```bash
npm install @agent-data-pipeline/agent-data-pipeline-api
```

## Usage

```javascript
import { AgentDataPipelineApi } from '@agent-data-pipeline/agent-data-pipeline-api';

const service = new AgentDataPipelineApi();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
