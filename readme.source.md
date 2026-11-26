```aura width=900 height=250
<div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', width: '100%', height: '100%', boxSizing: 'border-box', padding: '28px 38px', position: 'relative', overflow: 'hidden', borderRadius: 20, background: '#070B13', border: '1px solid #1B2A40', fontFamily: 'Inter, sans-serif' }}>
  <style>
    {`
      @keyframes title-breathe {
        0%, 100% { opacity: 0.92; }
        50% { opacity: 1; }
      }
      #hero-title { animation: title-breathe 5s ease-in-out infinite; }
    `}
  </style>
  <svg width="900" height="250" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="hero-cyan" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0, 205, 255, 0.22)" />
        <stop offset="100%" stopColor="rgba(0, 205, 255, 0)" />
      </radialGradient>
      <radialGradient id="hero-violet" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(114, 75, 255, 0.24)" />
        <stop offset="100%" stopColor="rgba(114, 75, 255, 0)" />
      </radialGradient>
      <pattern id="hero-grid" width="34" height="34" patternUnits="userSpaceOnUse">
        <path d="M 34 0 L 0 0 0 34" fill="none" stroke="rgba(148, 183, 220, 0.055)" strokeWidth="1" />
      </pattern>
      <linearGradient id="hero-edge" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stopColor="#15D8F5" stopOpacity="0.05" />
        <stop offset="48%" stopColor="#7A63FF" stopOpacity="0.8" />
        <stop offset="100%" stopColor="#15D8F5" stopOpacity="0.05" />
      </linearGradient>
    </defs>
    <rect width="900" height="250" fill="url(#hero-grid)" />
    <ellipse id="hero-orb-cyan" cx="780" cy="12" rx="260" ry="155" fill="url(#hero-cyan)">
      <animate attributeName="opacity" values="0.55;1;0.55" dur="8s" repeatCount="indefinite" />
    </ellipse>
    <ellipse id="hero-orb-violet" cx="155" cy="258" rx="250" ry="170" fill="url(#hero-violet)">
      <animate attributeName="opacity" values="1;0.5;1" dur="10s" repeatCount="indefinite" />
    </ellipse>
    <path d="M 38 214 H 862" stroke="url(#hero-edge)" strokeWidth="1" />
    <circle cx="862" cy="214" r="2.5" fill="#35E7F7">
      <animate attributeName="r" values="2;4;2" dur="2.8s" repeatCount="indefinite" />
    </circle>
  </svg>
  <div style={{ display: 'flex', flexDirection: 'column' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 9, marginBottom: 13, fontSize: 11, letterSpacing: 2.3, color: '#78D9E7', fontWeight: 700 }}>
      <span style={{ width: 7, height: 7, borderRadius: 4, background: '#35E7F7' }} />
      DATA ENGINEERING / CLOUD / DISTRIBUTED SYSTEMS
    </div>
    <div id="hero-title" style={{ display: 'flex', fontSize: 43, lineHeight: 1.05, letterSpacing: 0.6, fontWeight: 800, color: '#F3F7FF' }}>
      <span>AYUSH&nbsp;</span><span style={{ color: '#55E3F3' }}>SONAWANE</span>
    </div>
    <div style={{ display: 'flex', alignItems: 'center', gap: 12, marginTop: 12 }}>
      <span style={{ display: 'flex', fontSize: 15, letterSpacing: 2.2, fontWeight: 700, color: '#B9A6FF' }}>DATA ENGINEER</span>
      <span style={{ display: 'flex', width: 1, height: 17, background: '#324159' }} />
      <span style={{ display: 'flex', fontSize: 13, color: '#A8B5C9' }}>Cloud Data Platforms · Distributed Processing · AI/ML</span>
    </div>
    <div style={{ display: 'flex', marginTop: 13, fontSize: 12, color: '#8393AA', letterSpacing: 0.2 }}>
      Building dependable pipelines and platforms for data that moves ideas forward.
    </div>
  </div>
</div>
```

```aura width=176 height=48 link="https://github.com/Ayush-DataAnalyst" inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', gap: 10, width: '100%', height: '100%', borderRadius: 13, background: 'linear-gradient(135deg, #111A29, #0A111C)', border: '1px solid #263B55', color: '#E8F1FB', fontFamily: 'Inter, sans-serif', fontSize: 13, fontWeight: 650 }}>
  <svg width="18" height="18" viewBox="0 0 24 24">
    <path fill="#E8F1FB" d="M12 0C5.37 0 0 5.37 0 12c0 5.3 3.44 9.8 8.2 11.39.6.11.82-.26.82-.58v-2.23c-3.34.73-4.04-1.42-4.04-1.42-.55-1.39-1.34-1.76-1.34-1.76-1.1-.75.08-.74.08-.74 1.21.09 1.85 1.24 1.85 1.24 1.08 1.85 2.82 1.32 3.5 1.01.11-.78.42-1.32.76-1.63-2.67-.3-5.47-1.34-5.47-5.95 0-1.31.47-2.38 1.24-3.22-.12-.31-.54-1.52.12-3.17 0 0 1.01-.32 3.3 1.23.96-.27 1.98-.4 3-.4 1.02 0 2.05.13 3.01.4 2.28-1.55 3.29-1.23 3.29-1.23.66 1.65.24 2.86.12 3.17.77.84 1.24 1.91 1.24 3.22 0 4.62-2.8 5.64-5.48 5.94.43.37.81 1.1.81 2.22v3.29c0 .32.22.69.83.57A12.01 12.01 0 0 0 24 12C24 5.37 18.63 0 12 0z" />
  </svg>
  <span>GitHub profile</span>
</div>
```

```aura width=194 height=48 link="https://ultragravity.me" inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', gap: 9, width: '100%', height: '100%', borderRadius: 13, background: 'linear-gradient(135deg, #10152A, #0A111C)', border: '1px solid #3B3268', color: '#E6E0FF', fontFamily: 'Inter, sans-serif', fontSize: 13, fontWeight: 650 }}>
  <svg width="18" height="18" viewBox="0 0 24 24">
    <circle cx="12" cy="12" r="9" fill="none" stroke="#A99AFF" strokeWidth="1.5" />
    <path d="M3.5 12h17M12 3c2.3 2.4 3.4 5.4 3.4 9s-1.1 6.6-3.4 9c-2.3-2.4-3.4-5.4-3.4-9s1.1-6.6 3.4-9z" fill="none" stroke="#A99AFF" strokeWidth="1.25" />
  </svg>
  <span>Portfolio · ultragravity.me</span>
</div>
```

---

<p align="center"><a href="https://www.linkedin.com/in/ayush-sonawane1202/">LinkedIn</a></p>

## About

I’m a **Data Engineer** focused on scalable data pipelines, cloud data platforms, ETL workflows, warehouses, and distributed processing. My toolkit spans AWS, Python, SQL, PySpark, Spark, Databricks, dbt, Airflow, and Kafka; I also explore machine learning, generative AI, LLMs, and retrieval-augmented generation.

## Engineering focus

```aura width=900 height=278
(function() {
const items = [
  { n: '01', title: 'CLOUD DATA ENGINEERING', text: 'Scalable cloud pipelines, AWS ETL, data ingestion and cloud warehouses.', color: '#35D8EA' },
  { n: '02', title: 'BIG DATA & DISTRIBUTED SYSTEMS', text: 'PySpark processing, Spark optimization, Kafka streaming and distributed computing.', color: '#8C7BFF' },
  { n: '03', title: 'DATA PLATFORM ENGINEERING', text: 'Databricks, dbt, Airflow orchestration, lakehouse patterns and data quality.', color: '#4C9CFF' },
  { n: '04', title: 'AI & MACHINE LEARNING', text: 'Machine-learning workflows, LLM applications, RAG systems and AI-enabled solutions.', color: '#D58CFF' },
];
const CapabilityCard = ({ item }) => (
  <div style={{ display: 'flex', flexDirection: 'column', width: 420, height: 105, boxSizing: 'border-box', padding: '15px 17px', borderRadius: 14, background: 'linear-gradient(135deg, #101827, #0A111B)', border: '1px solid #1D2B40', position: 'relative', overflow: 'hidden', fontFamily: 'Inter, sans-serif' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 9, marginBottom: 8 }}>
      <span style={{ display: 'flex', color: item.color, fontSize: 11, fontWeight: 700, letterSpacing: 1.2 }}>{item.n}</span>
      <span style={{ display: 'flex', color: '#E4ECF8', fontSize: 12, fontWeight: 700, letterSpacing: 0.55 }}>{item.title}</span>
    </div>
    <div style={{ display: 'flex', color: '#97A6BA', fontSize: 12, lineHeight: 1.55 }}>{item.text}</div>
    <svg width="420" height="105" style={{ position: 'absolute', top: 0, left: 0 }}>
      <path d="M 18 103 H 116" stroke={item.color} strokeOpacity="0.75" strokeWidth="1.5">
        <animate attributeName="stroke-dasharray" values="0 100;70 100;0 100" dur="6s" repeatCount="indefinite" />
      </path>
    </svg>
  </div>
);
return (
<div style={{ display: 'flex', flexDirection: 'column', gap: 12, width: '100%', height: '100%', justifyContent: 'center', padding: 8, boxSizing: 'border-box', background: '#080D16', borderRadius: 18, fontFamily: 'Inter, sans-serif' }}>
  <div style={{ display: 'flex', gap: 12 }}>
    <CapabilityCard item={items[0]} />
    <CapabilityCard item={items[1]} />
  </div>
  <div style={{ display: 'flex', gap: 12 }}>
    <CapabilityCard item={items[2]} />
    <CapabilityCard item={items[3]} />
  </div>
</div>
);
})()
```

## Technology toolkit

Grouped by the work they support — not ranked by proficiency.

```aura width=900 height=404
(function() {
const groups = [
  { title: 'DATA ENGINEERING', items: 'Python · SQL · PySpark · Apache Spark · ETL · ELT · Data Warehousing · Data Modeling', color: '#35D8EA' },
  { title: 'CLOUD · AWS', items: 'AWS Glue · Amazon S3 · Amazon Redshift · AWS Lambda · AWS DMS · Athena · Step Functions · EMR', color: '#4C9CFF' },
  { title: 'BIG DATA', items: 'Apache Spark · PySpark · Kafka · Hadoop', color: '#8C7BFF' },
  { title: 'ORCHESTRATION', items: 'Apache Airflow · dbt · Databricks Workflows', color: '#D58CFF' },
  { title: 'DATABASES', items: 'PostgreSQL · SQL Server · Oracle · Amazon Redshift', color: '#5FC7AE' },
  { title: 'DEVOPS', items: 'Git · GitHub Actions · Docker · Linux', color: '#E8A15B' },
  { title: 'AI · MACHINE LEARNING', items: 'Machine Learning · Generative AI · LLMs · RAG · LangChain · Vector Search', color: '#DB79B8' },
];
const SkillCard = ({ item }) => (
  <div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', width: 420, height: 78, boxSizing: 'border-box', padding: '12px 16px', borderRadius: 12, background: '#0E1521', border: '1px solid #1B293B', fontFamily: 'Inter, sans-serif' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 8, marginBottom: 7 }}>
      <span style={{ display: 'flex', width: 6, height: 6, borderRadius: 4, background: item.color }} />
      <span style={{ display: 'flex', fontSize: 10, letterSpacing: 1.25, fontWeight: 700, color: item.color }}>{item.title}</span>
    </div>
    <div style={{ display: 'flex', fontSize: 11, lineHeight: 1.45, color: '#B2BED0' }}>{item.items}</div>
  </div>
);
return (
<div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', gap: 10, width: '100%', height: '100%', padding: 8, boxSizing: 'border-box', background: '#080D16', borderRadius: 18, fontFamily: 'Inter, sans-serif' }}>
  <div style={{ display: 'flex', gap: 10 }}><SkillCard item={groups[0]} /><SkillCard item={groups[1]} /></div>
  <div style={{ display: 'flex', gap: 10 }}><SkillCard item={groups[2]} /><SkillCard item={groups[3]} /></div>
  <div style={{ display: 'flex', gap: 10 }}><SkillCard item={groups[4]} /><SkillCard item={groups[5]} /></div>
  <div style={{ display: 'flex', gap: 10 }}><SkillCard item={groups[6]} /></div>
</div>
);
})()
```

## Selected projects

Selected from public repositories; descriptions reflect their READMEs and checked-in files.

```aura width=900 height=140 link="https://github.com/Ayush-DataAnalyst/Customer-Personality-Analysis"
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%', boxSizing: 'border-box', padding: '20px 25px', gap: 20, borderRadius: 16, background: 'linear-gradient(115deg, #101827, #0A111A)', border: '1px solid #26334B', fontFamily: 'Inter, sans-serif' }}>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center', width: 54, height: 54, borderRadius: 14, background: '#15263A', color: '#35D8EA', fontSize: 17, fontWeight: 700 }}>01</div>
  <div style={{ display: 'flex', flexDirection: 'column', flex: 1, gap: 7 }}>
    <span style={{ display: 'flex', color: '#74DCEB', fontSize: 10, letterSpacing: 1.7, fontWeight: 700 }}>MACHINE LEARNING · INTERACTIVE APP</span>
    <span style={{ display: 'flex', color: '#F0F5FD', fontSize: 19, fontWeight: 700 }}>Customer Personality Analysis</span>
    <span style={{ display: 'flex', color: '#9AA9BD', fontSize: 12 }}>KMeans customer segmentation with preprocessing, persisted models and a Streamlit prediction app.</span>
    <span style={{ display: 'flex', color: '#B8C8DE', fontSize: 10 }}>Python  /  KMeans  /  Streamlit  /  Docker</span>
  </div>
  <span style={{ display: 'flex', alignSelf: 'flex-start', color: '#8B9AB0', fontSize: 10, letterSpacing: 1 }}>OPEN REPOSITORY</span>
</div>
```

```aura width=900 height=140 link="https://github.com/Ayush-DataAnalyst/Hourly_Energy_Consumption_Forecasting"
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%', boxSizing: 'border-box', padding: '20px 25px', gap: 20, borderRadius: 16, background: 'linear-gradient(115deg, #111729, #0A111A)', border: '1px solid #29324B', fontFamily: 'Inter, sans-serif' }}>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center', width: 54, height: 54, borderRadius: 14, background: '#201C3B', color: '#A99AFF', fontSize: 17, fontWeight: 700 }}>02</div>
  <div style={{ display: 'flex', flexDirection: 'column', flex: 1, gap: 7 }}>
    <span style={{ display: 'flex', color: '#B1A5FF', fontSize: 10, letterSpacing: 1.7, fontWeight: 700 }}>TIME SERIES · FORECASTING</span>
    <span style={{ display: 'flex', color: '#F0F5FD', fontSize: 19, fontWeight: 700 }}>Hourly Energy Consumption Forecasting</span>
    <span style={{ display: 'flex', color: '#9AA9BD', fontSize: 12 }}>An LSTM-based Streamlit app for forecasting PJM hourly power consumption with interactive charts.</span>
    <span style={{ display: 'flex', color: '#B8C8DE', fontSize: 10 }}>Python  /  LSTM  /  Streamlit  /  Time Series</span>
  </div>
  <span style={{ display: 'flex', alignSelf: 'flex-start', color: '#8B9AB0', fontSize: 10, letterSpacing: 1 }}>OPEN REPOSITORY</span>
</div>
```

```aura width=900 height=140 link="https://github.com/Ayush-DataAnalyst/Project-Banking-Data-Analysis"
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%', boxSizing: 'border-box', padding: '20px 25px', gap: 20, borderRadius: 16, background: 'linear-gradient(115deg, #101A25, #0A111A)', border: '1px solid #25394A', fontFamily: 'Inter, sans-serif' }}>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center', width: 54, height: 54, borderRadius: 14, background: '#152B31', color: '#62D2B3', fontSize: 17, fontWeight: 700 }}>03</div>
  <div style={{ display: 'flex', flexDirection: 'column', flex: 1, gap: 7 }}>
    <span style={{ display: 'flex', color: '#70D6B8', fontSize: 10, letterSpacing: 1.7, fontWeight: 700 }}>ANALYTICS · BUSINESS INTELLIGENCE</span>
    <span style={{ display: 'flex', color: '#F0F5FD', fontSize: 19, fontWeight: 700 }}>Banking Data Analysis</span>
    <span style={{ display: 'flex', color: '#9AA9BD', fontSize: 12 }}>A banking analytics project with a SQL script, Python notebook and Power BI dashboard.</span>
    <span style={{ display: 'flex', color: '#B8C8DE', fontSize: 10 }}>Python  /  SQL  /  Jupyter  /  Power BI</span>
  </div>
  <span style={{ display: 'flex', alignSelf: 'flex-start', color: '#8B9AB0', fontSize: 10, letterSpacing: 1 }}>OPEN REPOSITORY</span>
</div>
```

## GitHub snapshot

Repository metrics and primary-language mix below are generated from GitHub's API at build time. Language share is based on the primary language of each public repository, not lines of code. GitHub's live contribution graph remains available on the [profile activity page](https://github.com/Ayush-DataAnalyst).

```aura width=900 height=230
(function() {
const stats = [
  { label: 'PUBLIC REPOSITORIES', value: String(github.stats.totalRepos), color: '#46D9EA' },
  { label: 'STARS', value: String(github.stats.totalStars), color: '#A99AFF' },
  { label: 'FORKS', value: String(github.stats.totalForks), color: '#68CDB3' },
];
const languages = github.languages.slice(0, 5);
return (
<div style={{ display: 'flex', width: '100%', height: '100%', boxSizing: 'border-box', padding: 20, gap: 24, borderRadius: 17, background: '#0A111B', border: '1px solid #1D2B40', fontFamily: 'Inter, sans-serif' }}>
  <div style={{ display: 'flex', flexDirection: 'column', width: 390, gap: 10 }}>
    <span style={{ display: 'flex', color: '#E6EEF9', fontSize: 11, letterSpacing: 1.5, fontWeight: 700 }}>PUBLIC REPOSITORY ACTIVITY</span>
    <div style={{ display: 'flex', gap: 9, marginTop: 4 }}>
      {stats.map((item) => (
        <div key={item.label} style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', width: 116, height: 105, padding: '0 12px', borderRadius: 12, background: '#101A28', border: '1px solid #1C2A3D' }}>
          <span style={{ display: 'flex', color: item.color, fontSize: 23, fontWeight: 750 }}>{item.value}</span>
          <span style={{ display: 'flex', color: '#8493A8', fontSize: 9, lineHeight: 1.35, marginTop: 6, letterSpacing: 0.6 }}>{item.label}</span>
        </div>
      ))}
    </div>
    <span style={{ display: 'flex', color: '#73839A', fontSize: 10, marginTop: 4 }}>Generated from public GitHub data</span>
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', flex: 1, gap: 11 }}>
    <span style={{ display: 'flex', color: '#E6EEF9', fontSize: 11, letterSpacing: 1.5, fontWeight: 700 }}>PRIMARY LANGUAGES · BY REPOSITORY</span>
    {languages.map((language) => (
      <div key={language.name} style={{ display: 'flex', alignItems: 'center', gap: 9 }}>
        <span style={{ display: 'flex', width: 92, color: '#AAB7CA', fontSize: 10 }}>{language.name}</span>
        <div style={{ display: 'flex', width: 210, height: 6, borderRadius: 4, background: '#182333', overflow: 'hidden' }}>
          <div style={{ display: 'flex', width: `${language.percentage}%`, height: 6, borderRadius: 4, background: language.color }} />
        </div>
        <span style={{ display: 'flex', width: 32, color: '#8594AA', fontSize: 10 }}>{language.percentage}%</span>
      </div>
    ))}
  </div>
</div>
);
})()
```

---

<p align="center">
  <strong>Building data systems. Exploring intelligent technologies. Engineering what comes next.</strong>
</p>

```aura width=900 height=58
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', overflow: 'hidden', position: 'relative', borderRadius: 14, background: '#080D16', border: '1px solid #1A2638', fontFamily: 'Inter, sans-serif' }}>
  <svg width="900" height="58" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <linearGradient id="footer-line" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stopColor="#35D8EA" stopOpacity="0" />
        <stop offset="50%" stopColor="#8C7BFF" stopOpacity="0.9" />
        <stop offset="100%" stopColor="#35D8EA" stopOpacity="0" />
      </linearGradient>
    </defs>
    <path d="M 50 47 H 850" stroke="url(#footer-line)" strokeWidth="1">
      <animate attributeName="stroke-dasharray" values="0 800;400 800;800 800" dur="7s" repeatCount="indefinite" />
    </path>
    <circle cx="450" cy="47" r="2" fill="#53DDEC">
      <animate attributeName="opacity" values="0.35;1;0.35" dur="3s" repeatCount="indefinite" />
    </circle>
  </svg>
  <span style={{ display: 'flex', color: '#91A2B8', fontSize: 11, letterSpacing: 1.4 }}>AYUSH SONAWANE&nbsp;&nbsp;·&nbsp;&nbsp;DATA ENGINEER</span>
</div>
```
