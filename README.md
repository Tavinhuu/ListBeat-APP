
<div align="center"> 
  <img height="100px" src="Letring Logo.png"/>
</div>
<br><br>
<p align="center">
  <strong>Seu catálogo musical pessoal.</strong><br/>
  Avalie, organize e redescubra suas músicas favoritas de forma independente.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-iOS-blue?logo=apple" />
  <img src="https://img.shields.io/badge/made%20with-SwiftUI-orange?logo=swift" />
  <img src="https://img.shields.io/badge/Node--RED-integrated-red?logo=node-red" />
  <img src="https://img.shields.io/badge/Cloudant-banco%20de%20dados-blue?logo=ibm" />
  <img src="https://img.shields.io/badge/projeto-HackaTruck%20Makerspace-yellow" />
</p>

---

## Sobre o projeto

**ListBeat** é um app iOS desenvolvido em SwiftUI como **projeto final do HackaTruck Makerspace**.  
A proposta é simples, porém poderosa: um **catálogo musical pessoal**, no estilo do Letterboxd (para filmes), mas voltado para **músicas e álbuns**.

Você pode adicionar músicas, avaliá-las, comentar, criar listas e acompanhar o seu histórico musical.

---

## Objetivo

Criar uma plataforma totalmente independente para que amantes de música possam organizar, avaliar e comentar sobre suas faixas e álbuns favoritos, como um diário musical pessoal e acessível.

---

## Tecnologias Utilizadas

- **Swift 5** — linguagem principal para desenvolvimento iOS
- **SwiftUI** — framework declarativo para construção de interfaces
- **Xcode** — ambiente de desenvolvimento oficial Apple
- **Node-RED** — ferramenta de lógica de backend baseada em fluxos
- **IBM Cloudant** — banco de dados NoSQL na nuvem, integrado ao app via API

---

### Pré-requisitos

- macOS com Xcode 13 ou superior
- Swift 5+
- Conta IBM Cloud (para Cloudant)
- Node-RED instalado localmente ou hospedado

### Passo a passo

```bash
git clone https://github.com/Tavinhuu/listbeat-APP
cd listbeat
open teste-api.xcodeproj
