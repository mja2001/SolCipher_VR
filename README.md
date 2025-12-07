Overview
SolCipher VR is an immersive, privacy-first decentralized application (dApp) for Meta Quest devices that revolutionizes secure document sharing between Solana wallets in virtual reality. It combines client-side AES-256-GCM encryption, decentralized IPFS storage, and Solana smart contracts for access control, all enhanced with intuitive hand interactions and mixed reality passthrough for a seamless spatial computing experience.
Innovation: The first privacy-first secure document sharing dApp in VR using Solana blockchain and IPFS, featuring natural hand interactions and passthrough mixed reality.
Competition Alignment:

Track: Lifestyle
Categories: Best Implementation of Hand Interactions + Best Experience Built with Spatial SDK

Problem Solved
Traditional file sharing requires leaving VR, breaking immersion. SolCipher VR enables users to securely share sensitive documents without removing their headset, using natural hand gestures and spatial UI.
Core Features

VR-Native Document Sharing
Upload and share encrypted documents entirely within VR
Natural hand tracking for file selection and manipulation
Spatial UI floating panels for intuitive interaction
Voice commands for accessibility

Mixed Reality Integration (Passthrough Camera)
View physical documents through passthrough camera
Scan QR codes from real-world documents using camera
Overlay document metadata in physical space
Context-aware AI to detect document types

Hand Interactions (No Controllers Required)
Pinch gestures to select files
Hand rays for pointing at UI elements
Two-handed gestures for document preview/zoom
Microgestures for quick actions (revoke, share, decrypt)
Direct touch UI for buttons and inputs

Blockchain Integration in VR
Solana wallet connection via QR code or deeplink
Transaction signing with hand gesture confirmation
Visual blockchain transaction feedback
Real-time on-chain access control visualization

Immersive 3D Document Visualization
3D holographic document previews
Spatial document gallery (floating documents around user)
Recipient visualization (avatar representations)
Access status indicators with particle effects

Social VR Features
Multi-user spaces for collaborative document review
Avatar system showing online contacts
Real-time document sharing notifications
Voice chat for secure communication


Technology Stack (Meta Horizon Optimized)
VR Platform

Platform: Meta Quest 3/Pro/2
Framework: Unity 2022.3 LTS or later
SDKs:
Meta XR SDK v81+ (All-in-One package)
Meta Spatial SDK v0.8.0+
Meta Hand Tracking SDK
Meta Passthrough API
Meta Voice SDK


Blockchain & Storage

Blockchain: Solana (Devnet/Mainnet)
Storage: IPFS via Web3.Storage
Wallet: WalletConnect for VR, Phantom mobile integration
Smart Contract: Anchor Framework (Rust)

Unity Implementation

Language: C#
Networking: Photon Unity Networking (PUN2) for multiplayer
UI Framework: Unity UI Toolkit + Spatial UI
Web3 Integration: Solana.Unity SDK / Nethereum
Encryption: System.Security.Cryptography

Architecture Workflow (VR-Optimized)

User enters VR environment
↓
Connect Solana wallet via QR code scan (passthrough camera)
↓
Navigate to upload zone with hand tracking
↓
Pinch gesture to open file browser OR Enable passthrough to capture physical document with camera
↓
Select recipient from spatial contact list
↓
Hand gesture to confirm encryption
↓
Request wallet signature (visualized in 3D space)
↓
Derive encryption key from signature
↓
Encrypt document with visual progress indicator
↓
Upload to IPFS with animated upload beam
↓
Create on-chain record with particle effect confirmation
↓
Document appears in recipient's VR space with notification

Recipient Workflow

Notification appears as floating hologram
↓
Pinch notification to open document preview
↓
Two-handed gesture to expand preview
↓
Verify on-chain access (visual chain animation)
↓
Request signature to decrypt (hand confirmation gesture)
↓
Document decrypts with particle dissolve effect
↓
View in immersive 3D space or download to device
