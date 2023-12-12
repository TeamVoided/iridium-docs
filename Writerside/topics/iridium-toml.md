# Iridium Toml

| projectTitle            | your project title                                                |
|-------------------------|-------------------------------------------------------------------|
| modId                   | your mod's id                                                     |
| githubRepo              | github repository (username/repo_name)                            |
| discordServerInviteId   | discord invite id (last bit of the url)                           |
| authors                 | array of author names                                             |
| majorMinecraftVersion   | major version of mc (ex. "1.20")                                  |
| minecraftVersion        | whole mc version (ex. "1.20.1")                                   |
| fabricLoaderVersion     | version of the fabricMC loader (ex. "1.14.21")                    |
| fabricApiVersion        | version of the fabric api (ex. "0.84.0+1.20.1")                   |
| fabricLangKotlinVersion | version of fabric lang kotlin (ex . "1.10.0+kotlin.1.9.0")        |
| license                 | license (ex. "MIT")                                               |
| modules                 | sub-gradle project / project modules (ex. ["module1", "module2"]) |
| mappings                | a mappings object (shown below)                                   |
{style="header-column"}

## Mappings Toml
| type    | mappings type (any of MOJANG, YARN, PARCHMENT, QUILT, MOJPARCH, MOJYARN) |
|---------|--------------------------------------------------------------------------|
| version | mappings version (irrelevant for MOJANG mappings)                        |
{style="header-column"}
