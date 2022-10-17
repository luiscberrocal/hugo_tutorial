# hugo_tutorial
Hugo tutorial to configure a blog

This is based on a theme in https://github.com/LukeSmithxyz/lugo

```shell
hugo new site new-site
cd new-site
git clone https://github.com/lukesmithxyz/lugo themes/lugo
echo "theme = 'lugo'" >> config.toml
cp themes/lugo/static/style.css static/
```