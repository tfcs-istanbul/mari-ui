---
"@mari-ui/cli": patch
---

AI kural dosyalarındaki link kuralı netleştirildi: `href` + `onNavigate` mari-ui component'leri için; uygulama içi kendi linklerinde router'ın `Link`'i, düz `<a href>` yalnız dış adres, indirme ve tam sayfa geçişleri için. Önceki "Linkler düz `<a href>`" ifadesi ajanların iç linkleri de düz yazmasına ve her tıklamada sayfanın baştan yüklenmesine yol açıyordu.
