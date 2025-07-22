export default function handler(req, res) {
  const min = 1;
  const max = 420;
  const visitors = Math.floor(Math.random() * (max - min + 1)) + min;

  res.setHeader('Access-Control-Allow-Origin', '*');  // <-- WICHTIG für CORS!
  res.setHeader('Cache-Control', 'no-store');
  res.status(200).json({ visitors });
}
