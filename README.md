# future-founders-app
{
  "name": "future-founders-app",
  "version": "1.0.0",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "13.4.12",
    "react": "18.2.0",
    "react-dom": "18.2.0"
  }
}{
  "compilerOptions": {
    "target": "es5",
    "lib": ["dom", "dom.iterable", "esnext"],
    "allowJs": true,
    "skipLibCheck": true,
    "strict": false,
    "forceConsistentCasingInFileNames": true,
    "noEmit": true,
    "esModuleInterop": true,
    "module": "esnext",
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "jsx": "preserve",
    "incremental": true
  },
  "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx"],
  "exclude": ["node_modules"]
}/** @type {import('next').NextConfig} */
const nextConfig = {}

module.exports = nextConfigexport default function Home() {
  return (
    <div style={{ padding: "2rem", fontFamily: "Arial" }}>
      <h1>Welcome to the Future Founders App</h1>
      <p>This is your starting point to become a founder.</p>
      <ul>
        <li>Challenge-based learning</li>
        <li>Founder Journey Dashboard</li>
        <li>AI Coach (coming soon)</li>
      </ul>
    </div>
  );
}body {
  margin: 0;
  padding: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial;
  background: #f5f5f5;
}{
  "version": 2
}