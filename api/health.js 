
export default function handler(req, res) {
  res.setHeader("Cache-Control", "no-store");

  if (req.method !== "GET") {
    return res.status(405).json({
      ok: false,
      message: "Method not allowed"
    });
  }

  return res.status(200).json({
    ok: true,
    service: "NOVYX Pay API",
    mode: "development",
    emailOtp: "not configured",
    smsOtp: "not configured",
    realPayments: false
  });
}
