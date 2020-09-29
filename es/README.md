# Traducciones de la comunidad de TensorFlow Docs

## Cuestiones

Problemas de traducción de la comunidad de archivos con el [rastreador tensorflow / docs-l10](https://github.com/tensorflow/docs-l10n/issues) .

Para problemas generales de documentación, use el rastreador en el [repositorio de tensorflow / tensorflow](https://github.com/tensorflow/tensorflow/issues/new?template=20-documentation-issue.md) .

# Traducciones comunitarias

Please read the [community translations](https://www.tensorflow.org/community/contribute/docs#community_translations) section in the [TensorFlow docs contributor guide](https://www.tensorflow.org/community/contribute/docs).

Haga preguntas generales en la [lista docs@tensorflow.org](https://groups.google.com/a/tensorflow.org/forum/#!forum/docs) , y hay algunas [listas de documentos específicos del idioma](https://www.tensorflow.org/community/contribute/docs#community_translations) para ayudar a coordinar las comunidades. Si un idioma está ganando impulso y los colaboradores piensan que sería útil una nueva lista específica del idioma, presente [un problema de GitHub](https://github.com/tensorflow/docs-l10n/issues) .

## Contenido

La fuente de la verdad para la documentación técnica es el directorio [site / en](https://github.com/tensorflow/docs/tree/master/site/en) en el [repositorio tensorflow / docs](https://github.com/tensorflow/docs/tree/master/site/en) . Si, al traducir, encuentra un problema en el contenido de origen, envíe una solicitud de extracción por separado que corrija el contenido original.

Para ver el contenido traducido en [tensorflow.org](https://www.tensorflow.org) , seleccione el selector de idioma en la página o agregue `?hl=<lang>` a la URL. Por ejemplo, el [tutorial de inicio rápido de TensorFlow 2 en](https://www.tensorflow.org/tutorials/quickstart/beginner?hl=en) inglés se puede leer en:

- Coreano: https://www.tensorflow.org/tutorials/quickstart/beginner?hl=ko
- Ruso: https://www.tensorflow.org/tutorials/quickstart/beginner?hl=ru
- O cualquiera de los idiomas admitidos en el [sitio /](https://github.com/tensorflow/docs-l10n/tree/master/site)<lang></lang> .

### Subsitios

Los subsitios son colecciones de documentos para proyectos fuera del *núcleo de TensorFlow* en el `tensorflow/docs` . Estos documentos suelen vivir con su proyecto en un repositorio de GitHub separado. Por ejemplo, los documentos de [tensorflow.org/federated se encuentran](https://www.tensorflow.org/federated) en el [repositorio de tensorflow / federated](https://github.com/tensorflow/federated/tree/master/docs) GitHub. Para las traducciones, refleje esta estructura *dentro de* este `tensorflow/docs-l10n` (es decir, no envíe solicitudes de extracción de traducción al repositorio del proyecto del subsitio).

### No traducir

Las siguientes secciones *no* están incluidas en el proyecto de traducciones de la comunidad. TensorFlow.org no traduce referencias de API y utiliza un sistema interno para páginas de destino y documentación sensible a la publicación. No traduzca las siguientes secciones:

- Cualquiera `/images/` directorios.
- Cualquier directorio `/r1/` (documentos de TensorFlow 1.x).
- El directorio `/install/` .
- Referencia de la API, incluidos los `/api_docs/` y `/versions/` .
- Navegación: archivos `_book.yaml` y `_toc.yaml` .
- Páginas de descripción general como `_index.yaml` , `index.html` e `index.md` .

## Estilo

Siga la [guía de estilo de la documentación de TensorFlow](https://www.tensorflow.org/community/contribute/docs_style) y la [guía de estilo de los documentos para desarrolladores de Google](https://developers.google.com/style/highlights) , cuando corresponda. Además, la comunidad puede acordar el estilo específico del idioma; consulte el archivo `README.md` dentro de un directorio `site/<lang>/` . Las propuestas y la comunicación de la comunidad pueden tener lugar a través de comentarios de solicitudes de extracción o listas de correo específicas del idioma (si están disponibles).

Para reducir la rotación de diferencias en las solicitudes de extracción de portátiles y facilitar las revisiones, utilice la herramienta [nbfmt](https://github.com/tensorflow/docs/blob/master/tools/nbfmt.py) o descargue el portátil de [Google Colab](https://colab.research.google.com/) .

## Licencia

[Licencia Apache 2.0](LICENSE)
