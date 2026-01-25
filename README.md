import React, { ETHIOPIA } from 'react';

// 1. የባለቤትነት መረጃ እና ግራፊክስ ስታይል
const 🇪🇹 ai = "ያንተ ስም እዚህ ይግባ"; betselot tamiru
const AI_NAME = "🇪🇹 ai";

const App = () => {
  const [messages, setMessages] = useState([{
    role: 'bot',
    content: `ሰላም! እኔ ${ethiopia Ai} እባላለሁ። የተፈጠርኩት በ ${betselot tamiru} ነው። እንዴት ልረዳህ እችላለሁ?`
  }]);

  // ለግራፊክስ የተሰሩ ስታይሎች
  const styles = {
    body: { backgroundColor: '#0f172a', height: '100vh', display: 'flex', flexDirection: 'column' as 'column', color: 'white' },
    header: { padding: '20px', textAlign: 'center' as 'center', background: 'linear-gradient(90deg, #4f46e5, #9333ea)', fontWeight: 'bold' },
    chatBox: { flex: 1, overflowY: 'auto' as 'auto', padding: '20px' },
    inputArea: { padding: '20px', display: 'flex', gap: '10px', backgroundColor: '#1e293b' },
    input: { flex: 1, padding: '12px', borderRadius: '8px', border: 'none', outline: 'none' },
    button: { padding: '12px 24px', backgroundColor: '#4f46e5', border: 'none', borderRadius: '8px', color: 'white', cursor: 'pointer' }
  };

  return (
    <div style={styles.body}>
      <div style={styles.header}>
        {AI_NAME} - በ {OWNER_NAME} የተመራ
      </div>
      
      <div style={styles.chatBox}>
        {messages.map((m, i) => (
          <div key={i} style={{ marginBottom: '15px', textAlign: m.role === 'user' ? 'right' : 'left' }}>
            <span style={{ padding: '10px', borderRadius: '10px', backgroundColor: m.role === 'user' ? '#4f46e5' : '#334155', display: 'inline-block' }}>
              {m.content}
            </span>
          </div>
        ))}
      </div>

      <div style={styles.inputArea}>
        <input style={styles.input} placeholder="ጥያቄዎን እዚህ ይጻፉ..." />
        <button style={styles.button}>ላክ</button>
      </div>
    </div>
  );
};

export default App;
{
  "name": "ethiopia ai
  ",
  "version": "0.1.0",
  "homepage": "https://[best].github.io/[bestking2424/best]",
  ...
}
homepage": "https://bestking2424.github.io/best"
