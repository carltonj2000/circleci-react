# Circle CI with React

[Netlify Deployed](wizardly-hopper-0b4c37.netlify.com)

## History

The code in this repository is based on
[Intro to CircleCI with React](https://www.youtube.com/watch?v=slGMKIDg7gM)
video.

## Notes

- Deploy vi circle ci and not netlify auto deploy. So create a dummy branch
  for netlify to watch and deploy from which never changes.
- Set NETLIFY_SITE_ID and NETLIFY_AUTH_TOKEN in Circle CI with information
  from netlify in order for the netlify deploy command in package.json to work.
