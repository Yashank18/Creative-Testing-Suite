# Creative-Testing-Suite
Create Website using API from themes by passing data or using same data and include custom add creatives to test your design before campaign.

## API Params
```sh
{
  authKey: string,
  template: {
    templateId: string,
    colorTheme: number,
    heading: string,
    type: mobile/website/in-app,
    themeType: string,
  },
  creatives: {
    sizes: Array of sizes,
    url: Array of Url maped to sizes,
  },
  callback: url,
}
```

## Output 
- Url will be returned as response or to callback URL, that url will host a website where your creatives will be organised as adds with sample data reagrding the selected theme. 
- URL will expire after 12 hours.  
