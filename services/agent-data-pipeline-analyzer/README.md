# agent-data-pipeline-analyzer

> Service: analyzer for Automated Data Pipeline Builder

## Installation

```bash
npm install @agent-data-pipeline/agent-data-pipeline-analyzer
```

## Usage

```javascript
import { AgentDataPipelineAnalyzer } from '@agent-data-pipeline/agent-data-pipeline-analyzer';

const service = new AgentDataPipelineAnalyzer();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
