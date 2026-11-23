# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- 移除 11 个第三方 git submodule 指针，改为 `docs/submodule-catalog.tsv` + 本 README 索引；克隆本仓无需 `git submodule`

### Added

- 父仓库初始化；将既有本地 clone 吸收为 11 个 git submodule（保留工作区文件，未重新下载）。

