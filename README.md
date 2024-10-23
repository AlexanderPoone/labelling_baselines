TODO: Refactor into an interactive Gradio app.

# Labelling baselines
Pretrained lightweight baseline models on some large corpora (Wikipedia, [OSCAR](https://github.com/oscar-project/ungoliant), or Common Crawl):
* ar: [asafaya/bert-large-arabic](https://github.com/alisafaya/Arabic-BERT), interestingly, by some guy from Koç University, Turkey    <- changed from 'base' to 'large'
* en: roberta-large    <- changed from 'base' to 'large'
* es: [dccuchile/albert-xxlarge-spanish](https://github.com/dccuchile/beto), aka BETO by DCC UChile    <- changed from `bert-base-spanish-wwm-cased` to `albert-xxlarge-spanish`
* fr: camembert-large    <- changed from 'base' to 'large'
* id: [indolem/indobert-base-uncased](https://github.com/indolem/indolem), by some guys from UniMelb    <- there is no cased version
* ja: bert-base-multilingual-cased    <- changed to cased
* ko: bert-base-multilingual-cased    <- changed to cased
* pt: [neuralmind/bert-large-portuguese-cased](https://github.com/neuralmind-ai/portuguese-bert), by a company named NeuralMind from São Paulo    <- changed from 'base' to 'large'
* ru: bert-base-multilingual-cased    <- changed to cased
* uk: [youscan/ukr-roberta-base](https://github.com/youscan/language-models), by a company named YouScan from Kyiv
* zh: bert-base-chinese

It all boils down to `(time, country, evt, category), sent=(positive|negative|controversial|apathy))`.
