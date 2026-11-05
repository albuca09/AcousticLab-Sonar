# AcousticLab Sonar — protótipo de interface

Protótipo web de análise acústica passiva com interface inspirada na imagem de referência fornecida.

## Executar

- **Localmente:** abra `index.html` no navegador.
- **GitHub Pages:** no repositório, use `Settings` > `Pages` > `Build and deployment` > `Deploy from a branch` > `main` / `(root)` e salve.
- O endereço publicado terá o formato `https://SEU-USUARIO.github.io/AcousticLab-Sonar/`.

## Funcionalidades do protótipo

- FFT/STFT e visualizações de espectrograma, sonograma e espectro;
- análise DEMON simplificada, controles de zoom, decimação e integração;
- importação de áudio, inclusive WAV PCM;
- demonstração por sinal sintético, com componentes de modulação conhecidas;
- modo experimental de microfone no contexto HTTPS, mediante permissão.

**Limitações:** Ainda não estão implementados os algoritmos Wigner–Ville, Nth Octave e SHM. O DEMON atual é exploratório e requer validação para uso científico/operacional. Não há backend Python hospedado no GitHub Pages nem armazenamento servidor de arquivos de áudio.

## Publicação pelo navegador, sem Terminal

1. Crie um repositório público no GitHub com nome `AcousticLab-Sonar`.
2. Em `Add file` > `Upload files`, envie **os arquivos extraídos** deste ZIP (principalmente `index.html`, `README.md` e `.nojekyll`), não o ZIP em si.
3. Conclua em `Commit changes`.
4. Configure `Settings` > `Pages` > `Build and deployment` > `Deploy from a branch` e escolha `main` / `(root)`.
5. Abra o endereço exibido em `Pages` após a publicação.

## Privacidade

GitHub Pages é uma publicação pública. Não inclua dados restritos ou gravações sensíveis. O código é um protótipo demonstrativo independente, não uma reprodução do software original.
