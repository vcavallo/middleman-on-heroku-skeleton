# Middleman on Heroku skeleton app

(thanks to [this guy's blog post](https://www.randomerrata.com/articles/2017/middleman-on-heroku/)]

- ruby 2.4.0
- middleman 4.2.1

This project has all the files and configuration needed to get Middleman running on Heroku. Should be as simple as setting up the Heroku project and pushing this to it (or preferably a cloned version of this with your site built on top of it..).

---

If you’re using an external asset pipeline that requires Node.js, you should add the Node.js buildpack to your Heroku app.

```
heroku buildpacks:set heroku/ruby
heroku buildpacks:add heroku/nodejs --index 1
```
