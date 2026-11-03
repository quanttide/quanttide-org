# Changelog

## Unreleased

### 变更

- `apps/qtcloud-org`：lite 部署链路接通（`deploy-lite.yml` + `manifests/terraform/lite.tf`/`cdn.tf`；OSS 桶 `qtcloud-org-lite`、CDN/DNS `lite.org.cloud.quanttide.com` 已建，首发待 `lite/*` tag，版本号由用户定）
- `apps/qtcloud-org` studio 新增架构编辑器（部门与岗位增改删 + 变更留痕）
- `apps/qtcloud-org` 新增 `src/lite`（量潮组织 Lite，Web 职务查表，载荷同步本批职务），拟替代 qtorg 站点
- 实验室子模块改名：`examples/default` → `examples/quanttide-org-lab`（仓 quanttide-laboratory-of-organization-management → quanttide-org-lab）


- 注册子模块：`data/library`（组织管理参考，quanttide-library-of-organization-management）
- 注册子模块：`apps/qtorg`（量潮组织中心，qtorg）
- 注册子模块：`data/brochure`（组织管理宣传册，quanttide-brochure-of-organization-management）
- 注册子模块：`docs/bylaw`、`docs/handbook`、`docs/specification`、`docs/tutorial`、`docs/essay`、`docs/gallery`（组织管理章程 / 手册 / 标准 / 教程 / 札记 / 案例集）

## 0.1.0 (2026-07-12)

- 初始化仓库
