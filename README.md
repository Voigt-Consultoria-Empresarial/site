# 🏢 Voigt Consultoria Empresarial - Site Institucional

Site institucional da Voigt Consultoria Empresarial com blog integrado via Supabase.

## 🚀 Início Rápido

### Desenvolvimento Local

O projeto está pronto para uso local. Basta abrir `index.html` no navegador.

### Produção (Netlify)

1. Configure as variáveis de ambiente no Netlify:
   - `VITE_SUPABASE_URL`
   - `VITE_SUPABASE_ANON_KEY`

2. O Netlify executará automaticamente o build command configurado em `netlify.toml`

## 📁 Estrutura do Projeto

```
├── index.html              # Página principal
├── 404.html                # Página de erro 404
├── blog/                   # Página de listagem do blog
├── blog-post/              # Página de post individual
├── sdk/                    # SDKs e configurações
├── scripts/                # Scripts de build
├── assets/                 # Imagens e recursos
└── netlify.toml            # Configuração do Netlify
```

## 🛠️ Scripts Disponíveis

```bash
# Gerar arquivo de configuração a partir de variáveis de ambiente
npm run build:config

# Verificar se tudo está configurado corretamente
npm run verify
```

## 🔒 Segurança

Este projeto utiliza variáveis de ambiente para armazenar credenciais do Supabase de forma segura. Veja `ENV-EXAMPLE.txt` para referência.

**Importante:** Nunca commite arquivos `.env` ou `sdk/config.js` com credenciais reais.

## 📚 Documentação Adicional

- **[README-TOPSTACK.md](./README-TOPSTACK.md)** - Informações sobre a TOPSTACK, empresa desenvolvedora

## 📞 Suporte

Para dúvidas ou problemas, consulte a documentação ou entre em contato.

---

**Desenvolvido por [TOPSTACK](https://topstack.com.br)**
