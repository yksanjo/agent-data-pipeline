# agent-data-pipeline-cli

> Package 4: cli for Automated Data Pipeline Builder

## Installation

```bash
npm install @agent-data-pipeline/agent-data-pipeline-cli
```

## Usage

```javascript
import { AgentDataPipelineCli } from '@agent-data-pipeline/agent-data-pipeline-cli';

const service = new AgentDataPipelineCli();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
