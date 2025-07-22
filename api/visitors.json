export default function handler(req, res) {
  const min = 120;
  const max = 420;

  const visitors = Math.floor(Math.random() * (max - min + 1)) + min;

  res.setHeader('Cache-Control', 'no-store');
  res.status(200).json({ visitors });
}
