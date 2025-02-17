# react-macronize 🪐

This component is totally invisible until a user triggers the [Konami Code](https://en.wikipedia.org/wiki/Konami_Code)... at which point they will see (and hear) macron yell across their screen!

### Installation

```sh
mkdir -p /path/to/your/project/src/macronize
cp -r src/* /path/to/your/project/src/macronize
```

### Demo

### Usage

```javascript
import { Macronize } from './macronize';

export const Component: React.FC = () => {
    return (
        <>
            <Macronize
                soundDelay={500} // Delay (ms) before playing audio
                sound // Should sound play at all
                repeat // Allow repeating the final code
                code // Display the code in the UI
                disabled={false} // Will this run at all
            />
        </>
    );
};
```

This project is a fork of [mewelling/react-raptorize](https://github.com/mewelling/react-raptorize)  
which is inspired by [formaweb/vanilla-raptorize](https://github.com/formaweb/vanilla-raptorize)...  
which itself was a port of the original [Zurb Raptorize](https://zurb.com/playground/jquery-raptorize).

### License

ISC
