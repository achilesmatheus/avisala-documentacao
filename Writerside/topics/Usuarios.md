# Usuários

## Arquitetura
Clean Archictecture
- Usuários.Api
- Usuários.Domain
- Usuarios.Infrastructure

## Partes a serem refatoradas

### Domain - AggregatesModel
- UsuárioAggregate/
    - UsuárioAggregate/
        - `Usuário.cs`


### Infrastructure - EntityConfigurations
- EntityTypeConfiguraton/
    - `UsuarioEntityTypeConfiguration.cs`


### Api - Application
- Commands/
    - `CreateUsuarioCommand.cs`
    - `CreateUsuarioCommandHandler.cs`
    - `RemoveUsuarioCommand.cs`
    - `RemoveUsuarioCommandHandler.cs`
    - `UpdateUsuarioCommand.cs`
    - `UpdateUsuarioCommandHandler.cs`
    - `VerificarExistenciaUsuarioCommand.cs`
    - `VerificarExistenciaUsuarioCommandHandler.cs`
- Queries/
    - `UsuariosQueries.cs`
- Validations/
    - `CreateUsuarioCommandValidator.cs`
    - `UpdateUsuarioCommandValidator.cs`
### Api - Grcp
