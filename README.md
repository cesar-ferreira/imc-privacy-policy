# imc-privacy-policy

Políticas de privacidade dos apps da Apps Sphere, publicadas como texto (Markdown sem extensão).

## Padrão (apps do Sphere Core, desde 22/11/2026)

- `<service>` = último trecho do applicationId (`br.com.appssphere.<service>`), o mesmo sufixo dos IDs
  dos produtos no iOS.
- Português: `<service>-policy-privacy`. Inglês: `english-<service>-policy-privacy`.
- Link: `https://raw.githubusercontent.com/cesar-ferreira/imc-privacy-policy/refs/heads/main/<arquivo>`.
- Fonte do texto: `docs/store/privacy-policy.md` de cada app (pt e en no mesmo arquivo). Mude lá e
  republique os dois arquivos aqui com a data nova.
- O app abre o link em inglês. Na App Store, a localização pt-BR usa o pt e as outras usam o en. Na
  Google Play (campo único), o en.
- Guia completo: `flutter-core/docs/LOJAS.md`.

| App | `<service>` | Português | Inglês |
|---|---|---|---|
| Birthday Countdown | `countdown` | [countdown-policy-privacy](countdown-policy-privacy) | [english-countdown-policy-privacy](english-countdown-policy-privacy) |
| Combinado | `combinado` | [combinado-policy-privacy](combinado-policy-privacy) | [english-combinado-policy-privacy](english-combinado-policy-privacy) |
| Kuido | `pet` | [pet-policy-privacy](pet-policy-privacy) | [english-pet-policy-privacy](english-pet-policy-privacy) |
| AutoGerente | `vehicle` | [vehicle-policy-privacy](vehicle-policy-privacy) | [english-vehicle-policy-privacy](english-vehicle-policy-privacy) |
| Shopping List | `shopeasy` | [shopeasy-policy-privacy](shopeasy-policy-privacy) | [english-shopeasy-policy-privacy](english-shopeasy-policy-privacy) |

Os outros arquivos são de apps anteriores ao Sphere Core e seguem os nomes que já estão nas lojas.
