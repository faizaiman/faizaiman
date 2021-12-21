# Faizznddn
<!--START_SECTION:waka-->
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
          WAKATIME_API_KEY: ${{ 20302e1e-9c6e-43a1-b72e-2db66f420a09}}
          GH_TOKEN: ${{ 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}}
<!--END_SECTION:waka-->
