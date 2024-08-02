# W3C WAI Website

- Live Website: https://www.w3.org/WAI/
- Preview: https://wai-website.netlify.com/

[![Netlify Status](https://api.netlify.com/api/v1/badges/faaa4954-0194-47fa-9b74-540ab79f4a8d/deploy-status)](https://app.netlify.com/sites/wai-website/deploys)

export const client = createClient({
  projectId: getSanityProjectId(),
  dataset: getSanityDataSet(),
  useCdn: false, // no edge cache
  apiVersion: "2022-03-07",
  perspective: "published",
});