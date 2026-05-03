# SimScale

SimScale is a cloud-based computer-aided engineering (CAE) platform offering computational fluid dynamics (CFD), finite element analysis (FEA), and thermal simulation capabilities. The SimScale REST API enables programmatic project management, geometry upload, mesh generation, simulation setup and execution, and results extraction for engineering automation workflows.

- **Website:** https://www.simscale.com
- **API Product:** https://www.simscale.com/product/api/
- **Documentation:** https://www.simscale.com/docs/platform/api-and-sdk-documentation/
- **Swagger UI:** https://api.simscale.com/apidoc/swagger/index.html
- **GitHub:** https://github.com/SimScaleGmbH
- **Python SDK:** https://github.com/SimScaleGmbH/simscale-python-sdk

## API

The SimScale REST API is available at `https://api.simscale.com`. Authentication uses an API key passed as the `X-API-KEY` header. API access requires an Enterprise plan.

## OpenAPI Specs

| Name | Description |
|---|---|
| [SimScale REST API](openapi/simscale-openapi.yml) | Full REST API covering projects, geometry, meshing, simulations, runs, and results |

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [simscale](capabilities/shared/simscale.yaml) | SimScale REST API consumed definition |

### Workflow Capabilities

| Capability | Description |
|---|---|
| [Simulation Automation](capabilities/simulation-automation.yaml) | End-to-end simulation pipeline: upload, mesh, simulate, retrieve results |

## Rules

| Name | Description |
|---|---|
| [SimScale Spectral Rules](rules/simscale-rules.yml) | Spectral ruleset enforcing SimScale API conventions |

## JSON Schema

| Name | Description |
|---|---|
| [Project Schema](json-schema/simscale-project-schema.json) | Schema for SimScale Project resource |
| [Simulation Schema](json-schema/simscale-simulation-schema.json) | Schema for SimScale Simulation resource |

## JSON Structure

| Name | Description |
|---|---|
| [Project Structure](json-structure/simscale-project-structure.json) | Structural documentation for Project, Geometry, Simulation, MeshOperation, SimulationRun |

## JSON-LD

| Name | Description |
|---|---|
| [SimScale Context](json-ld/simscale-context.jsonld) | JSON-LD context mapping SimScale terms to schema.org |

## Examples

| Name | Description |
|---|---|
| [Create Project](examples/simscale-create-project-example.json) | Example: creating a simulation project |
| [Create Simulation Run](examples/simscale-create-simulation-run-example.json) | Example: starting a simulation run |

## Vocabulary

| Name | Description |
|---|---|
| [SimScale Vocabulary](vocabulary/simscale-vocabulary.yml) | Domain terms for cloud CAE simulation |

## Maintainers

**API Evangelist**
- URL: https://apievangelist.com
- Email: info@apievangelist.com
