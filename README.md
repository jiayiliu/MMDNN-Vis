# MMDNN-Vis

Visualization tool branched from [MMdnn repo](https://github.com/Microsoft/MMdnn){:target="_blank"}.

## Development guide

### preparation

```bash
mmdownload -f cntk -n alexnet
mmtoir -f cntk -n AlexNet_ImageNet_CNTK.model -d ir_alexnet
```
### deploy to github page

Refer [here](https://gist.github.com/cobyism/4730490)

Do it after commit changes.

`git subtree push --prefix src origin gh-pages`

### local development

`node app.js`

## Roadmap
