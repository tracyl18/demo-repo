import logo from './logo.svg';
import logo2 from './home-icon-silhouette-svgrepo-com.svg';
import './App.css';


function App() {
  return (
    <div className="App">
      <header className="App-header">
	<div className="image123">
    		<div className="imageContainer">
        		<img src={logo} className="App-logo" alt="logo" width="200" height="200" align="left" />
		</div>
		<div className="imageContainer">
			<img src={logo2} className="App-logo2" alt="logo2" width="200" height="200" align="right"  />
 		</div>
	</div>
	<p>
          Hello! I have changed my message
        </p>
        <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer"
        >
          Learn React
        </a>
      </header>
    </div>
  );
}

export default App;
