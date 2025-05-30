import {
ArgTypes,
Canvas,
Controls,
Description,
Meta,
Subtitle,
Story,
} from '@storybook/blocks';

import \* as AvatarStories from './Avatar.stories';

# Avatar

<Meta of={AvatarStories} />

<Subtitle>Displays an image that represents a user or organization</Subtitle>

Use an avatar for attributing actions or content to specific users.

The user's name should _always_ be present when using Avatar – either printed beside the avatar or in a tooltip.

<Canvas>
  <Story of={AvatarStories.Standard} />
</Canvas>

<ArgTypes of={AvatarStories} />

## Additional variants

### Sizes

<Description of={AvatarStories.Sizes} />

<Story of={AvatarStories.Sizes} />

### Initials

<Description of={AvatarStories.Initials} />

<Story of={AvatarStories.Initials} />

### Loading

<Description of={AvatarStories.Loading} />

<Story of={AvatarStories.Loading} />

### Playground

Interact with the component and see how it responds to the different input properties.

<Canvas>
  <Story of={AvatarStories.Controls} />
</Canvas>

<Controls of={AvatarStories.Controls} />
