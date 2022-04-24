<div align="center">
    <h1>react-audio-control-z</h1>
    <br />
    <a href="https://codesandbox.io/s/434won">LIVE EXAMPLE</a>
</div>

---

#### Description
+ React simple control for record audio.
+ You can use it with some libs.  (ex: react-media-recorder, ...)
---

#### Usage
```js
npm install react-audio-control-z
```

Import the module in the place you want to use:
```js
import RecordControl from 'react-audio-control-z'
```

#### Snippet

##### `simple`

```js
    const [current, setCurrent] = useState(0)

    <br />
    {current}
    <br />
    <RecordControl
        lengthTime={60}
        durationTick={1000} // section
        setValue={setCurrent}
        // onStarting={() => {}}
        // onPausing={() => {}}
        // onReset={() => {}}
        // onCompleted={() => {}}
        // ...
    />


```
#### props
see in index.d.ts

#### RUN

<a href="https://codesandbox.io/s/434won">LIVE EXAMPLE</a>

```js
npm install
```
```js
npm run dev
npm run start
```

### License

MIT
