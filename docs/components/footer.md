# Footer

```handlebars
<EsFooter />
```


```handlebars
<EsFooter @tagline="A framework for ambitious web developers" />
```

```handlebars
{{!-- Check out the component blocks and their respective
configuration --}}
<EsFooter as |f|>
  <f.info infoLinks=infoLinks />
  <f.statement socialLinks=socialLinks />
  <f.contributions contributorLinks=contributorLinks />
</EsFooter>
```


```handlebars
{{!-- You can also add your own content on each component block --}}
<EsFooter as |f|>
  <f.info>
    <br/>
    <a>Team</a>
    <br/>
    <a>Contact</a>
  </f.info>
  <f.statement>
    Highly Productive Out of the Box
  </f.statement>
  <f.contributions>
    <div class="contributor">
      <p>Hosted by:</p>
      <a href="https://www.heroku.com/emberjs">
        Heroku
      </a>
    </div>
  </f.contributions>
</EsFooter>
```
