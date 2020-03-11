# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.1] - 2020-03-11
### Added
- Constants for Helen Hayes Model
- SequentialHelenHayes to spawn Helen Hayes Model entity from CSV file
- HelenHayesPositions to read positions from SequentialHelenHayes
- HelenHayesVelocities to calculate velocities from SequentialHelenHayes
- HelenHayesEntitiesHolder to hold entities as each position
- HelenHayesPositionsEntitiesSpawer to spawn entities and set HelenHayesEntitiesHolder
- HelenHayes*Effector to copy values to each entity of HelenHayesEntitiesHolder from SequentialHelenHeyas
- Hybrid/HelenHayesLineRenderer to render 5 lines as fitting Helen Hayes Model
- Hybrid/HelenHayesModelRenderer to render Specific Rig model
- *Deprecated* SequentialDataAsHelenHayesSpawner for independent entities spawn