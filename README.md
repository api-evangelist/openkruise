# OpenKruise (openkruise)

OpenKruise is a CNCF incubating project providing advanced workload management and deployment automation for Kubernetes. It extends Kubernetes with enhanced controllers including CloneSet for efficient stateless updates, Advanced StatefulSet with in-place updates, Advanced DaemonSet, SidecarSet for sidecar container management, BroadcastJob for node-level tasks, and ImagePullJob for pre-pulling container images.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openkruise/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openkruise/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Native
- Controllers
- Deployment
- Incubating
- Kubernetes
- Workload Management
- CRDs

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-28

## APIs

### OpenKruise Workload API

OpenKruise provides Kubernetes Custom Resource Definitions (CRDs) for advanced workload management. CloneSet offers efficient rolling updates with partition control, Advanced StatefulSet supports in-place container updates, Advanced DaemonSet provides surge and partitioned updates, SidecarSet manages sidecar containers across pods, BroadcastJob runs tasks on all nodes, and ImagePullJob pre-pulls images. Each controller extends standard Kubernetes capabilities with fine-grained deployment control through the apps.kruise.io/v1alpha1 and v1beta1 API groups.

- **Human URL:** [https://openkruise.io/docs/](https://openkruise.io/docs/)
- **Base URL:** `https://kubernetes.example.com/apis/apps.kruise.io/v1beta1`

#### Tags

- Deployment
- In-Place Updates
- Workload Controllers
- Kubernetes CRDs

#### Properties

- [Documentation](https://openkruise.io/docs/)
- [API Reference](https://openkruise.io/docs/reference/cloneset-api)
- [GitHub Repository](https://github.com/openkruise/kruise)
- [Postman Collection](collections/openkruise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openkruise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://openkruise.io/docs/)
- [Website](https://openkruise.io/)
- [Git Hub Org](https://github.com/openkruise)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
