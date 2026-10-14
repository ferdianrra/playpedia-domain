# PlaypediaDomain

Swift Package mandiri untuk entity gim, pilihan sorting, kontrak repository, dan use case katalog/favorit. Package ini memakai Foundation dan Combine; tidak bergantung pada SwiftUI, Alamofire, Swinject, Core Data, atau konfigurasi API RAWG.

Buka `Package.swift` dalam folder ini untuk memeriksa package secara terpisah. Build mandiri:

```sh
swift build --package-path Modules/PlaypediaDomain
```

Aplikasi saat ini menggunakannya melalui dependency lokal di manifest root. Implementasi repository berada di PlaypediaData; kontrak tetap berada di PlaypediaDomain. Tes domain berada di `Tests/GameUseCaseTests.swift` pada project aplikasi dan dijalankan melalui scheme Playpedia atau `swift test` dari root repository.
