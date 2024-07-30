# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '69249e46b6286e41ee47b5f51bf814881f15b63a',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '9bd6f95db3076517205b01300c8d37043c5b2dd3',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f013f08e4455bcc1f0eed8e3dd5e2009682656d9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '363486479d4c8dfbfdf2e2dc397cd10aa15f80b0',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '595c8d4794410a4e64b98dc58d27c0310d7ea2fd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e72ca6b705fe2fed43325b189e6122a5ce81a4af',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '46df205dcad665b652f57ee580d78051925b296a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '67522b34edde86dbb97e164280291f387ade55fc',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '716e05019354c6a70774a1299b66f753a10731ec',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
