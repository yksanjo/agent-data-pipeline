# agent-data-pipeline-monitor

> Service: monitor for Automated Data Pipeline Builder

## Installation

```bash
npm install @agent-data-pipeline/agent-data-pipeline-monitor
```

## Usage

```javascript
import { AgentDataPipelineMonitor } from '@agent-data-pipeline/agent-data-pipeline-monitor';

const service = new AgentDataPipelineMonitor();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
