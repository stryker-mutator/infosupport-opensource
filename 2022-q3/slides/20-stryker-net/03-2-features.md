# Features

- Support YAML as config file format @LiamCottrell
- Support more azure storage API and SAS formats @LiamCottrell
- Support full azure storage SAS format @tidusjar
    Breaking:
    SAS must contain `sv=` and `sig=` to be valid. SAS without sv= are no longer transformed to valid SAS.
