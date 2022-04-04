---
title: Building the new Hopper.com in 2018
date: 2018-04-31
hero: "/images/hero-2.jpg"
excerpt: Creating a new website for Hopper, one of the top 4 most downloaded travel
  apps in the U.S, along with Uber, Lyft.
timeToRead: 4
authors:
- Dennis Brotzky

---
Business has changed at an accelerated pace in recent years and the digital era is already with us. The advantages of adapting and including digital strategies to your business are huge.

The digital era has arrived and businesses must take into account that implementing a digital marketing strategy is essential for their growth in this era, but how to start? Any change at the beginning can be complicated, but here are some of the factors that you can define and make this process a path full of learning.

• Know how your company works, its objectives and establish processes that all your staff knows and applies.

• Understand your customers' needs and the way they seek information about services or products.

```js
import React from "react";
import { graphql, useStaticQuery } from "gatsby";
import styled from "@emotion/styled";

import * as SocialIcons from "../../icons/social";
import mediaqueries from "@styles/media";

const icons = {
  dribbble: SocialIcons.DribbbleIcon,
  linkedin: SocialIcons.LinkedinIcon,
  twitter: SocialIcons.TwitterIcon,
  facebook: SocialIcons.FacebookIcon,
  instagram: SocialIcons.InstagramIcon,
  github: SocialIcons.GithubIcon,
};

const socialQuery = graphql`
  {
    allSite {
      edges {
        node {
          siteMetadata {
            social {
              name
              url
            }
          }
        }
      }
    }
  }
`;

function SocialLinks({ fill = "#73737D" }: { fill: string }) {
  const result = useStaticQuery(socialQuery);
  const socialOptions = result.allSite.edges[0].node.siteMetadata.social;

  return (
    <>
      {socialOptions.map(option => {
        const Icon = icons[option.name];

        return (
          <SocialIconContainer
            key={option.name}
            target="_blank"
            rel="noopener"
            data-a11y="false"
            aria-label={`Link to ${option.name}`}
            href={option.url}
          >
            <Icon fill={fill} />
          </SocialIconContainer>
        );
      })}
    </>
  );
}
```

This is another paragraph after the code block.

## By understanding this two factors, you have already complete half of the process.

![](/images/banner-digital-reputation-03.png)

```jsx
import React from "react";
import { ThemeProvider } from "theme-ui";
import theme from "./theme";

export default props => (
  <ThemeProvider theme={theme}>{props.children}</ThemeProvider>
);
```

You can be really surprised how the digital era is affecting business, in fact, there are many areas that you would never have thought before that would migrate to this type of digital communication.

For example, lawyers, due to the need for their services and the context in which the market is, seek customers through social media offering their services and

emphasizing their added value. To this end, they include the Digital Marketing MUSTS for lawyers in their digital strategies.

Also, Medical Digital Marketing, why not? In this pandemic we have realized how important it is to be informed about health issues and for this reason doctors have chosen to create strategies in which their added value is to make themselves known about the knowledge they have and thus attract more patients.

These are just some of the areas in which the digital era is penetrating with great intensity and bringing benefits to businesses and brands that dare to opt for this new modality.

Our team is more than willing to continue working with you and trace the path in which you can meet more goals in your business. Click here to contact you directly and include the digital marketing era into your business DNA.