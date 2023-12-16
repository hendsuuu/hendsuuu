START_SECTION:waka
### Hi there 👋

SHOW_LANGUAGE:waka

name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: waka_76eb5c82-2f32-4ddb-a119-2006470e177e
          GH_TOKEN: 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
          
END_SECTION:waka

