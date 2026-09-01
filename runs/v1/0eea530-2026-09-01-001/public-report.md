## Weave Agent Evals Report — 🔴 One or more suites failed

**Git SHA**: `0eea530` | **Assembled**: 2026-09-01T20:13:56.305Z

**Total cases**: 175 | **Passed**: 80 | **Failed**: 95
**Suites**: loom-routing, tapestry-execution, shuttle-execution, spindle-tools, pattern-planning, weft-review, warp-security, tapestry-category-routing

### Suite: loom-routing — 🔴 red

**Total**: 21 | **Passed**: 20 | **Failed**: 1

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| loom-route-ambiguous-direct-shuttle | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-opus-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-opus-5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | openai/gpt-5.6-sol | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | openai/gpt-5.6-sol | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |

### Suite: tapestry-execution — 🟢 green

**Total**: 14 | **Passed**: 14 | **Failed**: 0

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| tapestry-delegate-to-shuttle | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required delegation case partially passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required delegation case partially passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | openai/gpt-5.5 | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | anthropic/claude-opus-5 | ⚠️ partial | yes | required delegation case partially passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | openai/gpt-5.6-sol | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | qwen/qwen3.8-max | ⚠️ partial | yes | required delegation case partially passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required delegation case partially passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: shuttle-execution — 🔴 red

**Total**: 14 | **Passed**: 9 | **Failed**: 5

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| shuttle-execution-report-structured-evidence | anthropic/claude-opus-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-opus-4.5 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | openai/gpt-5.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | openai/gpt-5.5 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | anthropic/claude-opus-5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | openai/gpt-5.6-sol | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | qwen/qwen3.8-max | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | qwen/qwen3.8-max | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: spindle-tools — 🔴 red

**Total**: 14 | **Passed**: 11 | **Failed**: 3

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| spindle-tools-citations-facts-confidence | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | anthropic/claude-sonnet-4.5 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | deepseek/deepseek-v4-flash-0731 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |

### Suite: pattern-planning — 🔴 red

**Total**: 14 | **Passed**: 5 | **Failed**: 9

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| pattern-plan-release-checklist | anthropic/claude-opus-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-opus-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | openai/gpt-5.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | openai/gpt-5.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | anthropic/claude-opus-5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-opus-5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | openai/gpt-5.6-sol | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | openai/gpt-5.6-sol | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | qwen/qwen3.8-max | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | qwen/qwen3.8-max | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | deepseek/deepseek-v4-flash-0731 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |

### Suite: weft-review — 🔴 red

**Total**: 14 | **Passed**: 9 | **Failed**: 5

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| weft-review-clean-approval | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | openai/gpt-5.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | anthropic/claude-opus-5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | qwen/qwen3.8-max | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: warp-security — 🔴 red

**Total**: 14 | **Passed**: 12 | **Failed**: 2

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| warp-security-block-evidence-findings | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | anthropic/claude-opus-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| warp-security-fast-exit-approve | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: tapestry-category-routing — 🔴 red

**Total**: 70 | **Passed**: 0 | **Failed**: 70

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| tcr-01-exact-match | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-02-multiple-files | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-03-windows-paths | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-04-no-match | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-05-cross-category | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-06-overlap | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-07-explicit-hint | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-08-misleading-prose | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-09-similar-names | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-10-disabled-category | anthropic/claude-opus-4.5 | ❌ fail | no |  |
| tcr-01-exact-match | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-02-multiple-files | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-03-windows-paths | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-04-no-match | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-05-cross-category | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-06-overlap | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-07-explicit-hint | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-08-misleading-prose | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-09-similar-names | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-10-disabled-category | anthropic/claude-sonnet-4.5 | ❌ fail | no |  |
| tcr-01-exact-match | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-02-multiple-files | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-03-windows-paths | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-04-no-match | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-05-cross-category | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-06-overlap | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-07-explicit-hint | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-08-misleading-prose | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-09-similar-names | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-10-disabled-category | openai/gpt-5.5 | ❌ fail | no |  |
| tcr-01-exact-match | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-02-multiple-files | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-03-windows-paths | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-04-no-match | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-05-cross-category | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-06-overlap | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-07-explicit-hint | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-08-misleading-prose | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-09-similar-names | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-10-disabled-category | anthropic/claude-opus-5 | ❌ fail | no |  |
| tcr-01-exact-match | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-02-multiple-files | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-03-windows-paths | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-04-no-match | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-05-cross-category | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-06-overlap | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-07-explicit-hint | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-08-misleading-prose | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-09-similar-names | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-10-disabled-category | openai/gpt-5.6-sol | ❌ fail | no |  |
| tcr-01-exact-match | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-02-multiple-files | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-03-windows-paths | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-04-no-match | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-05-cross-category | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-06-overlap | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-07-explicit-hint | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-08-misleading-prose | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-09-similar-names | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-10-disabled-category | qwen/qwen3.8-max | ❌ fail | no |  |
| tcr-01-exact-match | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| tcr-02-multiple-files | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| tcr-03-windows-paths | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| tcr-04-no-match | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| tcr-05-cross-category | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| tcr-06-overlap | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| tcr-07-explicit-hint | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| tcr-08-misleading-prose | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| tcr-09-similar-names | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| tcr-10-disabled-category | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
