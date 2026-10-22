# Rule-Config

Rule configs for proxy clients.

## Mihomo

Pass as the subconverter `config` parameter.

`RuleSet`: rules expanded by the backend, with ad blocking.

```text
https://raw.githubusercontent.com/KilluaAoki/Rule-Config/main/Mihomo/RuleSet/Config.toml
```

`RuleProviders`: rule providers with the full group set, with ad blocking.

```text
https://raw.githubusercontent.com/KilluaAoki/Rule-Config/main/Mihomo/RuleProviders/Config.toml
```

`RuleProviders_Streamlined`: fewer groups, no ad blocking.

```text
https://raw.githubusercontent.com/KilluaAoki/Rule-Config/main/Mihomo/RuleProviders_Streamlined/Config.toml
```

## Shadowrocket

Add under Config, then set Global Routing to Config.

`Default`: no policy groups, no ad blocking.

```text
https://cdn.jsdelivr.net/gh/KilluaAoki/Rule-Config@main/Shadowrocket/Default.conf
```

`AdBlock`: `Default` with ad blocking.

```text
https://cdn.jsdelivr.net/gh/KilluaAoki/Rule-Config@main/Shadowrocket/AdBlock.conf
```

`Groups`: per-service policy groups, same rules as `RuleProviders`.

```text
https://cdn.jsdelivr.net/gh/KilluaAoki/Rule-Config@main/Shadowrocket/Groups.conf
```
