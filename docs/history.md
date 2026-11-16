1. created this project entire folder with pnpm create next-app@latest [name-of-app] --yes
2. created Claude.md
3. created project-doc.md
4. claude plugin install frontend-design@claude-plugins-official
5. Inside supabase UI click connect:
5.1. launch: ```
npm install @supabase/supabase-js @supabase/ssr
```
5.2. add .env.local files
5.3. add DB PWD in env
5.4. run ```npx skills add supabase/agent-skills```

6. Go to doc: https://supabase.com/docs/guides/ai-tools/mcp
6.1. run ```claude mcp add --scope project --transport http supabase "https://mcp.supabase.com/mcp?features=docs%2Caccount%2Cdatabase%2Cdebugging%2Cdevelopment%2Cfunctions%2Cbranching%2Cfeedback%2Cnotebooks"```




