# Customer Needs Research / 客户需求研究

[本轮真实 Sol 6.1 场景、首稿与审阅 / agent behavior evidence](cases/agent-behavior-2026-10-16/README.md) — 合成输入，不代表真实调研或业务效果。

Start with the [LanternDesk synthetic needs brief](examples/fictional-example.md): inputs → need clusters → trade-offs → counterevidence → next check. [Blank brief](references/output-template.md) · [Skill entry](SKILL.md). / 先看合成需求示例，再填简报。

## English
A personal-use marketing workflow skill to turn permitted customer evidence into clear needs, messaging implications, and validation questions. This skill is continuously updated as practical learning develops; no release schedule, maintenance commitment, or research outcome is guaranteed. This is a lightweight first version, not a production research platform.

### Use
Give an AI agent SKILL.md and a short business brief: product, audience, market, decision, and any existing evidence. Example request: “Use this skill to compare the permitted tutor feedback below. Cluster unmet needs, include contrary notes, choose one landing-page research angle and list what must be validated.” Return a needs brief with source IDs, separate observation/inference/hypothesis, prioritization reasons, counterevidence and neutral follow-up questions. The skill itself grants no account access. Public web or connected read-only tools are optional; supplied-material analysis works offline with limitations disclosed.

### Workflow and decisions
1. **You** provide the decision, audience and permitted feedback; clarify material gaps or disclosure limits when asked.
2. **AI** inventories sources, deduplicates notes and clusters needs, keeping observations, inferences and counterexamples separate.
3. **You** assess which supported needs matter for the business and what requires customer validation; sample counts are not market prevalence.
4. **AI** hands back the needs brief, source coverage, trade-offs and neutral follow-up questions for your review; no customer contact is performed.

### Contents
- SKILL.md: agent workflow and evidence safeguards
- references/output-template.md: reusable deliverable structure
- examples/fictional-example.md: clearly synthetic demonstration, never actual research
- THIRD_PARTY_NOTICES.md and licenses/: verified upstream source and retained license

### Attribution and boundaries
Adapted from [Nicolabaldo/user-pain-research-skill](https://github.com/Nicolabaldo/user-pain-research-skill/tree/213cbc6cd1f56ad12836aa7fee7ddb7d89425813) for task fit, not popularity. See THIRD_PARTY_NOTICES.md for exact scope and rights. No repository-wide license has been selected for original contributions. Upstream material retains its applicable license; this does not change those rights. No scripts, paid services, automatic credentials, publication, or hidden integrations are included. Validation is structural review plus a fictional walkthrough, not live effectiveness testing.

## 中文
这是个人使用的营销工作流技能，用于把获准使用的客户反馈整理为需求、营销启示与验证问题。项目会随实践持续更新，但不承诺固定更新频率、维护服务或研究效果。目前是轻量首版。

示例请求：“请用 [SKILL.md](SKILL.md) 整理我提供的导师反馈，区分情况与需求，保留反例，选一个值得继续调查的落地页角度。”交付需求简报、来源台账、取舍理由与中性访谈问题；观察、推断和待验证假设分开。先复用获准上下文，只追问关键缺口；没有浏览工具就说明仅分析已给资料。

### 流程与判断
1. **你**提供业务决策、受众和获准反馈；必要时补关键事实或披露边界。
2. **AI**盘点来源、去重并归纳需求，分开观察、推断和反例。
3. **你**判断需求与业务的关系、取舍及后续验证方向，不把样本频次当市场比例。
4. **AI**交付需求简报、来源覆盖、取舍和中性追问，供你审阅；不执行客户联系。

输出模板在 references/；examples/ 中全部为虚构演示，不是真实案例。真实观察、分析推断和待验证假设必须分开。不会自动安装集成、读取凭据、联系客户、付费调研或发布内容。

上游模块采用 MIT；来源、固定提交、修改说明和完整许可文本已保留。原创部分尚未选择仓库级许可证。质量检查限于结构与虚构走读，不代表真实营销成效已验证。
