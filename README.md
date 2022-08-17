<!--
parent:
  order: false
-->

<div align="center">
  <h1> Cosmos SDK </h1>
</div>

![banner](docs/cosmos-sdk-image.jpg)

<div align="center">
  <a href="https://github.com/cosmos/cosmos-sdk/blob/main/LICENSE">
    <img alt="License: Apache-2.0" src="https://img.shields.io/github/license/cosmos/cosmos-sdk.svg" />
  </a>
  <a href="https://pkg.go.dev/github.com/cosmos/cosmos-sdk">
    <img src="https://pkg.go.dev/badge/github.com/cosmos/cosmos-sdk.svg" alt="Go Reference">
  </a>
  <a href="https://goreportcard.com/report/github.com/cosmos/cosmos-sdk">
    <img alt="Go report card" src="https://goreportcard.com/badge/github.com/cosmos/cosmos-sdk" />
  </a>
  <a href="https://codecov.io/gh/cosmos/cosmos-sdk">
    <img alt="Code Coverage" src="https://codecov.io/gh/cosmos/cosmos-sdk/branch/main/graph/badge.svg" />
  </a>
</div>
<div align="center">
  <a href="https://github.com/cosmos/cosmos-sdk">
    <img alt="Lines Of Code" src="https://tokei.rs/b1/github/cosmos/cosmos-sdk" />
  </a>
  <a href="https://discord.gg/AzefAFd">
    <img alt="Discord" src="https://img.shields.io/discord/669268347736686612.svg" />
  </a>
  <a href="https://sourcegraph.com/github.com/cosmos/cosmos-sdk?badge">
    <img alt="Imported by" src="https://sourcegraph.com/github.com/cosmos/cosmos-sdk/-/badge.svg" />
  </a>
    <img alt="Sims" src="https://github.com/cosmos/cosmos-sdk/workflows/Sims/badge.svg" />
    <img alt="Lint Satus" src="https://github.com/cosmos/cosmos-sdk/workflows/Lint/badge.svg" />
</div>

Cosmos SDK, blok zinciri uygulamaları oluşturmak için bir faramework'tür. [Tendermint Core (BFT Consensus)](https://github.com/tendermint/tendermint) ve Cosmos SDK, Golang programlama dilinde yazılmıştır. Cosmos SDK, Cosmos Hub'ın ilk uygulaması olan [Gaia](https://github.com/cosmos/gaia)'yı oluşturmak için kullanılır. 

**UYARI**: Cosmos SDK'sı büyük ölçüde stabilize edilmiştir, ancak hala bazı önemli değişiklikler yapıyoruz.

**Not**: [Go 1.18+](https://go.dev/dl) gereklidir.

## Hızlı Başlangıç

Cosmos SDK'nın üst düzey bir perspektiften nasıl çalıştığını öğrenmek için Cosmos SDK [High-Level Intro](./docs/intro/overview.md)'ya bakın

Hızlı bir şekilde başlamak ve Cosmos SDK'nın üzerine nasıl inşa edildiğini öğrenmek istiyorsanız, [Cosmos SDK Tutorials](https://tutorials.cosmos.network) adresini ziyaret ediniz. Kendi Cosmos SDK uygulamanızı oluşturmaya başlamak için öğreticinin deposunu da forklayabilirsiniz.

Daha fazla bilgi için bkz. [Cosmos SDK Documentation](./docs/).

## Katkıda Bulunun

[Geliştirme çağrılarımıza](./CONTRIBUTING.md#teams-dev-calls) nasıl katkıda bulunabileceğinizi ve katılabileceğinizi öğrenmek için [CONTRIBUTING.md](./CONTRIBUTING.md) adresine bakın.

Güncellemeleri takip etmek ya da en son tasarım hakkında daha fazla bilgi edinmek istiyorsanız [Discord](https://discord.com/invite/cosmosnetwork) sayfamıza katılın.

## Araçlar ve Frameworks

Cosmos ekosistemi çok geniştir. Burada sadece dikkate değer birkaç konudan bahsedeceğiz.

+ [Tools](https://v1.cosmos.network/tools): önemli frameworkler ve modüller.
+ [CosmJS](https://github.com/cosmos/cosmjs): JavaScript tabanlı istemci çözümlerini güçlendirmek için İsviçre Çakısı.

### Cosmos Hub Mainnet

Cosmos Hub uygulaması `gaia` kendi [cosmos/gaia deposuna](https://github.com/cosmos/gaia) taşındı. Cosmos Hub ana ağına ve daha fazlasına katılmak için oraya bakın.

### Inter-Blockchain Communication (IBC)

Cosmos SDK için IBC modülü kendi [cosmos/ibc-go deposuna](https://github.com/cosmos/ibc-go) taşındı. IBC modülünü oluşturmak ve entegre etmek için oraya bakın.

### Ignite CLI

Ignite CLI, bağımsız ve güvenli bir blok zincirinde herhangi bir kripto uygulamasını oluşturmak, başlatmak ve sürdürmek için hepsi bir arada platformudur. Yeni bir uygulama veya yeni bir modülü oluşturuyorsanız, başlamak ve geliştirmeyi hızlandırmak için [Ignite CLI](https://github.com/ignite/cli) kullanın.

## Anlam Ayrımı / Belirsizliği Giderme

Bu Cosmos SDK projesi, [React-Cosmos](https://github.com/react-cosmos/react-cosmos) projesiyle (henüz) ilgili değildir. Bu GitHub organizasyon adı için Evan Coury ve Ovidiu (@skidding)'ya çok teşekkürler. Anlaşmamıza göre, bu anlam ayrımı bildirimi burada kalacak.
