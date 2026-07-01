## Weave Agent Evals Report — 🔴 One or more suites failed

**Git SHA**: `40c1cee` | **Assembled**: 2026-07-01T05:47:51.278Z

**Total cases**: 45 | **Passed**: 30 | **Failed**: 15
**Suites**: loom-routing, tapestry-execution, shuttle-execution, spindle-tools, pattern-planning, weft-review, warp-security

### Suite: loom-routing — 🔴 red

**Total**: 9 | **Passed**: 5 | **Failed**: 4

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| loom-route-ambiguous-direct-shuttle | anthropic/claude-opus-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-opus-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-sonnet-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-sonnet-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |

### Suite: tapestry-execution — 🟢 green

**Total**: 6 | **Passed**: 6 | **Failed**: 0

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| tapestry-delegate-to-shuttle | anthropic/claude-opus-4.5 | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required delegation case partially passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | openai/gpt-5.5 | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: shuttle-execution — 🔴 red

**Total**: 6 | **Passed**: 5 | **Failed**: 1

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| shuttle-execution-report-structured-evidence | anthropic/claude-opus-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-opus-4.5 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | openai/gpt-5.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: spindle-tools — 🔴 red

**Total**: 6 | **Passed**: 4 | **Failed**: 2

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| spindle-tools-citations-facts-confidence | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | anthropic/claude-sonnet-4.5 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: pattern-planning — 🔴 red

**Total**: 6 | **Passed**: 1 | **Failed**: 5

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| pattern-plan-release-checklist | anthropic/claude-opus-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-opus-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
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
