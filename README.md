This dbt project uses a postgres databased running inside a docker container.
Please see the logs from dbt debug. Note this uses a Conda Environment.

```
(dagster_py39) mymac:jaffle_shop peeyushu$ dbt debug --profiles-dir /Users/peeyushu/LDocuments/github-personal/dagster-dbt/scheduled_jaffle_shop/.dbt
04:28:59  Running with dbt=1.6.7
04:28:59  dbt version: 1.6.7
04:28:59  python version: 3.9.18
04:28:59  python path: /opt/homebrew/anaconda3/envs/dagster_py39/bin/python3.9
04:28:59  os info: macOS-14.2-arm64-arm-64bit
04:28:59  Using profiles dir at /Users/peeyushu/LDocuments/github-personal/dagster-dbt/scheduled_jaffle_shop/.dbt
04:28:59  Using profiles.yml file at /Users/peeyushu/LDocuments/github-personal/dagster-dbt/scheduled_jaffle_shop/.dbt/profiles.yml
04:28:59  Using dbt_project.yml file at /Users/peeyushu/LDocuments/github-personal/dagster-dbt/scheduled_jaffle_shop/jaffle_shop/dbt_project.yml
04:28:59  adapter type: postgres
04:28:59  adapter version: 1.6.7
04:28:59  Configuration:
04:28:59    profiles.yml file [OK found and valid]
04:28:59    dbt_project.yml file [OK found and valid]
04:28:59  Required dependencies:
04:28:59   - git [OK found]

04:28:59  Connection:
04:28:59    host: localhost
04:28:59    port: 5432
04:28:59    user: postgres
04:28:59    database: mydb
04:28:59    schema: public
04:28:59    connect_timeout: 10
04:28:59    role: None
04:28:59    search_path: None
04:28:59    keepalives_idle: 0
04:28:59    sslmode: None
04:28:59    sslcert: None
04:28:59    sslkey: None
04:28:59    sslrootcert: None
04:28:59    application_name: dbt
04:28:59    retries: 1
04:28:59  Registered adapter: postgres=1.6.7
04:28:59    Connection test: [OK connection ok]

04:28:59  All checks passed!
```

Welcome to your new dbt project!


### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
