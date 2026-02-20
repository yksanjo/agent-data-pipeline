# agent-data-pipeline-core

> Package 1: core for Automated Data Pipeline Builder

## Installation

```bash
npm install @agent-data-pipeline/agent-data-pipeline-core
```

## Usage

```javascript
import { AgentDataPipelineCore } from '@agent-data-pipeline/agent-data-pipeline-core';

const service = new AgentDataPipelineCore();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
