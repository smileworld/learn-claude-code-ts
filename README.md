# learn-claude-code-ts

A playground repository for learning Claude Code with TypeScript.

## Quick Start

You need [Node.js](https://nodejs.org/) 18+ (it bundles `npm`). The repository does not ship a `package.json` yet, so the first run also creates one:

```bash
# 1. Clone the repository
git clone https://github.com/smileworld/learn-claude-code-ts.git
cd learn-claude-code-ts

# 2. Create package.json
npm init -y

# 3. Install the TypeScript toolchain as dev dependencies
npm install --save-dev typescript tsx @types/node
```

Write a TypeScript file, for example `hello.ts` containing `console.log("hello, claude code");`, and run it directly with [tsx](https://www.npmjs.com/package/tsx):

```bash
npx tsx hello.ts
```

Any `*.ts` file runs the same way: `npx tsx <file>.ts`.

Initialized by the dsh-superagent test deployment (agent account: smilekj).
