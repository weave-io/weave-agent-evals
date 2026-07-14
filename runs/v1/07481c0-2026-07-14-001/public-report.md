## Weave Agent Evals Report — 🔴 One or more suites failed

**Git SHA**: `07481c0` | **Assembled**: 2026-07-14T18:46:24.851Z

**Total cases**: 75 | **Passed**: 34 | **Failed**: 41
**Suites**: loom-routing, tapestry-execution, shuttle-execution, spindle-tools, pattern-planning, weft-review, warp-security, tapestry-category-routing

### Suite: loom-routing — 🔴 red

**Total**: 9 | **Passed**: 7 | **Failed**: 2

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| loom-route-ambiguous-direct-shuttle | anthropic/claude-opus-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-sonnet-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |

### Suite: tapestry-execution — 🟢 green

**Total**: 6 | **Passed**: 6 | **Failed**: 0

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| tapestry-delegate-to-shuttle | anthropic/claude-opus-4.5 | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | openai/gpt-5.5 | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: shuttle-execution — 🔴 red

**Total**: 6 | **Passed**: 5 | **Failed**: 1

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| shuttle-execution-report-structured-evidence | anthropic/claude-opus-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | openai/gpt-5.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | openai/gpt-5.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |

### Suite: spindle-tools — 🔴 red

**Total**: 6 | **Passed**: 4 | **Failed**: 2

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| spindle-tools-citations-facts-confidence | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: pattern-planning — 🔴 red

**Total**: 6 | **Passed**: 3 | **Failed**: 3

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| pattern-plan-release-checklist | anthropic/claude-opus-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-opus-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | openai/gpt-5.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | openai/gpt-5.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |

### Suite: weft-review — 🔴 red

**Total**: 6 | **Passed**: 4 | **Failed**: 2

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| weft-review-clean-approval | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: warp-security — 🔴 red

**Total**: 6 | **Passed**: 5 | **Failed**: 1

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| warp-security-block-evidence-findings | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | anthropic/claude-opus-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: tapestry-category-routing — 🔴 red

**Total**: 30 | **Passed**: 0 | **Failed**: 30

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
