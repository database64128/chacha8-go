# chacha8-go

ChaCha8 & ChaCha8-Poly1305 in Go, modified from the ChaCha20 & ChaCha20-Poly1305 implementations in `x/crypto` to use 8 rounds instead of 20.

Currently only the generic implementation is guaranteed to be correct. All assembly implementations are best-effort and may not be correct.

## License

The code is derived from `x/crypto` and thus is licensed under the same terms as `x/crypto`. See [LICENSE](LICENSE) for more information.
