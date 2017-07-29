# Eazy Ease

![eazy e](https://i.imgur.com/TcS91qR.jpg)

`npm install --save eazy-ease`

## Styled Components Example

```
import { easeInOutCirc } from 'eazy-ease';

const MiniCartWrapper = styled.div`
  width: 100%;
  min-height: 247px;
  z-index: 10;
  padding: 20px 40px;
  transition: 0.3s ${easeInOutCirc} all;
`;

```