# CENTURY × JETOUR — projeto integrado para Vercel

## Publicar
1. Extraia o ZIP.
2. Envie o conteúdo da pasta para um repositório GitHub privado.
3. Importe na Vercel como framework Other, sem build.
4. Abra o site e acesse **Atlas e plantas**.

## Conteúdo
- index.html: gestão de pessoas, fornecedores, veículos, equipamentos, importação em massa, operações e atlas integrado no mesmo HTML.
- assets/: seis imagens de plantas, mais ilustração de conceito (NÃO cartográfica).
- plantas/: PDFs originais e imagens de visualização.

## Bússola
Botão Ativar sensor: tenta obter rumo do dispositivo quando navegador e hardware fornecem orientação absoluta. Em computadores e sensores sem direção absoluta permanece norte fixo, sem simular orientação. Precisa HTTPS e permissão em certos dispositivos. A orientação do desenho não deve ser confundida com a orientação do aparelho.

## Segurança / limitações
Versão estática sem backend, autenticação ou sincronização entre dispositivos. Dados ficam no localStorage do navegador. Não publicar dados pessoais ou documentos sensíveis em arquivos estáticos; para operação multiusuário implementar Supabase com RLS, auditoria e controle de acesso. Rotas e portões não foram aprovados pela administração do estádio. Ilustração não é fotografia aérea nem base cartográfica.
