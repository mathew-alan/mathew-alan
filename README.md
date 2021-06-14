- 👋 Hi, I’m @mathew-alan
-class HelloMessage extends React.Component {
  render() {
    return (
      <div>
        Hello {this.props.name}
      </div>
    );
  }
}

ReactDOM.render(
  <HelloMessage name="Mathew" />,
  document.getElementById('hello-example')
);
