# DDoS Attack Map

A student-built DDoS Attack Map that demonstrates real-time visualization of global attack telemetry.  
It fetches free-tier data from **Cloudflare Radar** and **AbuseIPDB**, classifies malicious IPs using lightweight machine learning, geolocates them, and renders live attack flows on a 3D globe frontend.  
The backend is powered by **FastAPI**, while the frontend uses **React + deck.gl + MapLibre**.

---

## 🚀 Features
- FastAPI backend with REST endpoints and WebSocket streaming
- Integration with Cloudflare Radar (traffic trends, attack spikes)
- Optional AbuseIPDB lookup for IP reputation
- GeoIP2 database for IP-to-location mapping
- React frontend with deck.gl for globe-based visualization
- Real-time attack event updates

