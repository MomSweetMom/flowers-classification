# Deploying Flower Classification models on [Render](https://render.com)

Dataset: [102 Flower Category Database](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/)

Test app locally

```bash
python app/server.py serve
```

Test with Docker:

```bash
docker build -t flower-classification . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.
