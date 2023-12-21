# Aluguel de Carros

## Descrição do Projeto
Bem-vindo ao repositório do projeto "Aluguel de Carros". Neste projeto, desenvolvi uma aplicação do tipo Console capaz de gerenciar operações básicas de um sistema de aluguel de carros. A aplicação controla diversos tipos de veículos, status de locações e os processos de locação e cancelamento.

## Requisitos do Projeto
### 1. Crie uma Struct para as Cores
- [Color.cs](src/RentCars/Types/Structs/Color.cs) implementado com sucesso.
  - A struct contém os campos `Name` e `Hex` do tipo string, ambos públicos.

### 2. Crie um enum FuelType
- [FuelType.cs](src/RentCars/Types/Enums/FuelType.cs) implementado com sucesso.
  - O enum contém os campos `Alcohol`, `Gasoline`, `Flex`, `Diesel`, `Electric` e `Hybrid` com valores específicos.

### 3. Crie a classe Vehicle
- [Vehicle.cs](src/RentCars/Models/Vehicle.cs) implementado com sucesso.
  - A classe possui propriedades para `Brand`, `Model`, `Price`, `Fuel`, `EngineCapacity`, `MainColor`, `Year`, `PricePerDay`, e `IsRented`.

### 4. Crie um enum BrakeType
- [BrakeType.cs](src/RentCars/Types/Enums/BrakeType.cs) implementado com sucesso.
  - O enum contém os campos `Chamber`, `Disc` e `Drum` com valores específicos.

### 5. Crie um enum TractionType
- [TractionType.cs](src/RentCars/Types/Enums/TractionType.cs) implementado com sucesso.
  - O enum contém os campos `FrontWheelDrive`, `RearWheelDrive` e `AllWheelDrive` com valores específicos.

### 6. Faça a classe Car herdar de Vehicle
- [Car.cs](src/RentCars/Models/Car.cs) implementado com sucesso.
  - A classe `Car` herda corretamente de `Vehicle` e inclui novas propriedades específicas para carros.

### 7. Faça a classe Motorcycle herdar de Vehicle
- [Motorcycle.cs](src/RentCars/Models/Motorcycle.cs) implementado com sucesso.
  - A classe `Motorcycle` herda corretamente de `Vehicle` e inclui novas propriedades específicas para motos.

### 8. Faça a classe PickupTruck herdar de Car
- [PickupTruck.cs](src/RentCars/Models/PickupTruck.cs) implementado com sucesso.
  - A classe `PickupTruck` herda corretamente de `Car` e inclui novas propriedades específicas para caminhonetes.

### 9. Crie um enum RentStatus
- [RentStatus.cs](src/RentCars/Types/Enums/RentStatus.cs) implementado com sucesso.
  - O enum contém os campos `Confirmed`, `Finished` e `Canceled` com valores específicos.

### 10. Crie o construtor de Rent seguindo as regras de negócio
- [Rent.cs](src/RentCars/Models/Rent.cs) implementado com sucesso.
  - O construtor recebe instâncias de `Vehicle`, `Person` e um valor inteiro com os dias alugados.
  - O preço é calculado conforme regras de negócio.
  - O status inicial é `RentStatus.Confirmed`.
  - O construtor altera o atributo `IsRented` do veículo para true.
  - O construtor altera o atributo `Debit` da pessoa para o preço calculado.

## Habilidades Técnicas
- Linguagem: C#
- Paradigma: Programação Orientada a Objetos (POO)
- Tecnologias: .NET
- Estrutura: Console Application
- Controle de Versão: Git

