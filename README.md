# .github

Org-wide defaults for the `VendorSage` org (the company is **Node**; the org login is
unchanged by the rebrand).

GitHub serves anything in `.github/ISSUE_TEMPLATE/` here to **every repo in the org that has
no `.github/ISSUE_TEMPLATE/` of its own**. A repo with its own templates ignores these
entirely.

## What is here, and what is deliberately not

Only **Task** — the one issue type that gets filed in a code repo.

`product-engineering` owns the other three (Product Epic, Planning work, Decision needed)
because all of them produce something that lives in that repo: a phase spanning several
repos, or a document that merges there. It also has its own templates, so it never inherits
from here.

Blank issues stay enabled. A code repo needs a way to file a quick bug without ceremony, and
forcing every one through the Task form would just get worked around.

## Changing the Task template

Edit `.github/ISSUE_TEMPLATE/task.yml` and push. It takes effect immediately in every repo
that inherits it — there is no per-repo copy to update. Keep it in step with
[`product-engineering`](https://github.com/VendorSage/product-engineering)'s own `task.yml`,
which is the version that repo uses.
