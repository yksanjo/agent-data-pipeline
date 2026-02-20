# agent-data-pipeline-connectors

> Package 5: connectors for Automated Data Pipeline Builder

## Installation

```bash
npm install @agent-data-pipeline/agent-data-pipeline-connectors
```

## Usage

```javascript
import { AgentDataPipelineConnectors } from '@agent-data-pipeline/agent-data-pipeline-connectors';

const service = new AgentDataPipelineConnectors();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
