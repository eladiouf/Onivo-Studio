# Validation Surface

## Verification Surfaces

- `src/test/java/` targeted unit coverage
- Gradle `test`
- Gradle `build`
- Gradle `runClient` when runtime behavior must be checked

## Known Pressure

- external mod APIs and mixins can drift
- large integration slices can leave documentation behind
- local logs and scratch artifacts can obscure signal during audits
