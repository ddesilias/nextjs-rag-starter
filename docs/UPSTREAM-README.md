# RAG Starter

Expérimentation d’un assistant connecté à une base de connaissances avec Next.js, TypeScript et le Vercel AI SDK.

- Ressources et embeddings stockés dans PostgreSQL.
- Schéma et migrations avec Drizzle.
- API de chat avec recherche de contexte.

Consulter `.env.example` pour les variables attendues et la documentation d’origine ci-dessous pour l’installation.

La connexion PostgreSQL utilise `DATABASE_URL`, ou `POSTGRES_URL` lorsque cette
variable est fournie par l’intégration Vercel Postgres. Les identifiants restent
dans les variables d’environnement du serveur.

---

# Vercel AI SDK RAG Guide Starter Project

This is the starter project for the Vercel AI SDK [Retrieval-Augmented Generation (RAG) guide](https://sdk.vercel.ai/docs/guides/rag-chatbot).

In this project, you will build a chatbot that will only respond with information that it has within its knowledge base. The chatbot will be able to both store and retrieve information. This project has many interesting use cases from customer support through to building your own second brain!

This project will use the following stack:

- [Next.js](https://nextjs.org) 14 (App Router)
- [Vercel AI SDK](https://sdk.vercel.ai/docs)
- [OpenAI](https://openai.com)
- [Drizzle ORM](https://orm.drizzle.team)
- [Postgres](https://www.postgresql.org/) with [ pgvector ](https://github.com/pgvector/pgvector)
- [shadcn-ui](https://ui.shadcn.com) and [TailwindCSS](https://tailwindcss.com) for styling
